properties([
  parameters([
    string(name: 'Version', description: 'Possible options: 1 1.1 1.2 1.3', defaultValue: ''),
    string(name: 'Application', description: 'Possible options: .net java', defaultValue: 'defvalue'),
   
  ])
])
node("master")
{
  def a = "localvariablevalue"
    stage("Checkout")
{
  echo "${a}"
  echo "${param1}"
  
  echo "${param2}"
  
  echo "${param3}"
  
  echo "${param4}"
  
}
    
    stage("Build")
    {
        echo "Sample build"
    }

}

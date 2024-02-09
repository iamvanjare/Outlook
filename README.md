# Install Exchange Online PowerShell V3 module
  
  ## 1. Set Windows PowerShell Execution Policy
      
      Set-ExecutionPolicy RemoteSigned

  ## 2. Install PowerShellGet module   

      Install-Module PowershellGet -Force
  
  ## 3. Install Exchange Online Management module
    
      Install-Module -Name ExchangeOnlineManagement -Force

  ##    Connect to Exchange Online PowerShell V3

      Connect-ExchangeOnline -UserPrincipalName admin@exoip.com
    
 ##   Start Archive
 
     start-managedfolderassistant -Identity UserPrinciple0

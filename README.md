# Integrate-PDQ-Install-Into-MDT-Imaging
Integrates PDQ Install Into Your MDT Imaging Process

During the MDT Process add the following line to each application you would like to deploy

powershell.exe -executionpolicy bypass -noprofile -file "\\server\deploymentshare$\Scripts\PDQ_Remote.ps1" "PDQ Package Name"

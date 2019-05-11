# Introduction 
My notes when going through the book Docker on Windows (Second Edition)

# Chapter 1
## Page 22
Install Docker Engine EE on Windows

```powershell
Install-Module -Name DockerMsftProvider -Repository PSGallery -Force

Install-Package -Name docker -ProviderName DockerMsftProvider
```

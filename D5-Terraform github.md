# Creating GitHub repositories using terraform

## Obtaining access tokens

- *Needed for authentication to access the repo using terraform without uname and pswd.*

&nbsp;

1.  Go to GitHub and sign in
    
2.  Inside GitHub, generate a Personal Access Token
    
3.  Click on settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token
    
4.  Give it a name and choose an expiration date
    
5.  Select repositories as "All repositories"
    
6.  Under "Repository Permisions",
    
7.  Set "Administration" to "Read and Write".
    
8.  Generate the token
    

## Terraform

`provider "github" {`  
`token = "`<token>"</token>  
<token>}</token>

`resource "github_repository" "example" {`  
`name = "repo name"`  
`description = "My codebase"`

`visibility = "public"`  
`}`

1.  Cd into main.tf folder using gitbash
2.  terraform init 
3.  terraform fmt 
4.  terraform plan 
5.  terraform apply

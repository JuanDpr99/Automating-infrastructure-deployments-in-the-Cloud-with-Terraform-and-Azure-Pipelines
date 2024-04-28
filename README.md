# Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines 
[https://www.azuredevopslabs.com/](https://www.azuredevopslabs.com/)

## Que es Terraform
- Terraform es una herramienta de infraestructura como código que le permite crear, cambiar y versionar recursos en la nube y locales de forma segura y eficaz.
  
 ![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/d3b3521f-5b61-4cec-862d-a34fa4eb60bd)

# Antes de iniciar
## Crea un nuevo proyecto en Azure Devops 

Ingresar al siguiente [Link](https://azuredevopsdemogenerator.azurewebsites.net/?TemplateId=77382&Name=Terraform)

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/a7bce872-9df5-4b05-8326-fa472cf952b7)

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/54078c53-f71e-4fcf-9fb4-7f31fba24f61)

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/ab348ae4-f292-46c8-a4b4-4412943c4e5c)

[Link de MyProjectDemo en azure](https://dev.azure.com/CVDS-Parroquiano/MyProjectDemo)




## Errores que presente al momento de crear un proyecto

No tener deshabilitado esta opción en la organización 

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/8ca760fb-57e0-4327-9bd1-88173490459c)


Habilitar este check en la organizaciónn

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/a7f2f5d6-6478-4bd1-a207-323690bd6d0b)

Asegura tener instalado estas dos extensiones en la organización 

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/5dbb7f52-de5d-4165-b0aa-7a8af45930e5)


Buscar en la tienda y descargar

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/7cd046bf-eb7f-4493-8cb4-9a11ac9c8197)


## Exercise 1: Examine the Terraform file (IaC) in your Source code

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/86b8e565-9915-49a1-9c4a-21d7845e593b)

webapp.tf es un archivo de configuración de Terraform. Terraform utiliza su propio formato de archivo, llamado HCL (Hashicorp Configuration Language). Esto es muy similar a YAML.

En este ejemplo, queremos implementar un grupo de recursos de Azure, un plan de servicio de aplicaciones y un servicio de aplicaciones necesarios para implementar el sitio web. Y hemos agregado el archivo Terraform (Infraestructura como código) al repositorio de control de código fuente en su proyecto Azure DevOps que puede implementar los recursos de Azure necesarios.


## Exercise 2: Build your application using Azure CI Pipeline

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/b34bd4ee-bb8a-47ac-98cb-dd117849880f)


![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/c60d5779-3ef7-4e21-8c34-f9161e4bd67b)

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/381396d6-4d69-476a-8b51-b6577df0b3b6)


LLenar el siguiente [formulario](https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR5zsR558741CrNi6q8iTpANURUhKMVA3WE4wMFhHRExTVlpET1BEMlZSTCQlQCN0PWcu) 

![image](https://github.com/JuanDpr99/Automating-infrastructure-deployments-in-the-Cloud-with-Terraform-and-Azure-Pipelines/assets/77819591/3f5adf7f-efb2-45d8-8eba-00a456a5a90f)






# Terraform Basics - Mi Primer Proyecto IaC

Proyecto práctico de **Infrastructure as Code** con Terraform.

## Qué he hecho
- Instalación y configuración de Terraform en Ubuntu (WSL2).
- Creación de un recurso local con el provider `local_file`.
- Uso completo del ciclo de vida: `terraform init`, `plan`, `apply` y `destroy`.
- Buenas prácticas: `.gitignore` correcto y documentación clara.

## Tecnologías
- Terraform (v1.9+)
- Local provider

## Cómo ejecutarlo

```bash
terraform init          # Instala providers
terraform plan          # Muestra qué va a hacer
terraform apply -auto-approve   # Crea el archivo
terraform destroy -auto-approve # Limpia todo

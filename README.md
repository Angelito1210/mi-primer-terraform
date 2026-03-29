# Mi Primer Proyecto Real con Terraform en AWS

Proyecto práctico de **Infrastructure as Code (IaC)** donde despliego una página web estática en un bucket de S3 usando Terraform.

## Qué he hecho
- Creación de un bucket S3 con Terraform.
- Configuración de hosting estático (website configuration).
- Política pública para que la web sea accesible.
- Subida automática del archivo `index.html` al bucket.
- Limpieza completa del entorno con `terraform destroy`.

## Tecnologías utilizadas
- Terraform (v1.9+)
- AWS S3 + Static Website Hosting
- Provider AWS + random_string

## Cómo ejecutarlo

```bash
# 1. Inicializar Terraform
terraform init

# 2. Ver qué va a crear
terraform plan

# 3. Desplegar
terraform apply -auto-approve

# 4. (Opcional) Limpiar todo cuando termine
terraform destroy -auto-approve

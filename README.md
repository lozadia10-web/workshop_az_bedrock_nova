# workshop_az_bedrock_nova
# Workshop: AI Agent con AWS Bedrock & Terraform 🚀
**Bootcamp:** Cloud Computing - BeTek

Este proyecto consiste en el despliegue de una infraestructura completa en AWS para soportar un Agente de IA. Utiliza una arquitectura orientada a microservicios con despliegue automatizado.

## 🌐 Demo del Proyecto
Puedes ver el agente funcionando en la siguiente URL (mientras la infraestructura esté activa):
👉 [http://aws-bucket-ai-agent-dianalozano-v2.s3-website-us-east-1.amazonaws.com/](http://aws-bucket-ai-agent-dianalozano-v2.s3-website-us-east-1.amazonaws.com/)

## 🏗️ Arquitectura del Proyecto
- **Frontend:** Aplicación web estática (HTML/JS/CSS) alojada en **Amazon S3**.
- **API:** Punto de enlace administrado mediante **Amazon API Gateway** (HTTP API).
- **Lógica (Backend):** Procesamiento de datos con **AWS Lambda** usando Python y la librería Boto3.
- **Infraestructura como Código (IaC):** Despliegue automatizado mediante **Terraform**.

## 📁 Estructura de Carpetas
```text
.
├── app/
│   ├── frontend/     # Archivos de la web estática
│   └── lambda/       # Código de la función Lambda y lambda.zip
├── infra/            # Scripts de Terraform (.tf)
├── .github/          # Configuraciones de automatización (Workflows)
└── README.md

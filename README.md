# AWS WebApp Dashboard

Petit dashboard web pour gérer les **instances EC2** et les **buckets S3**.

## Fonctionnalités

- Lister les instances EC2
- Lister, créer et supprimer des buckets S3
- Uploader des fichiers vers un bucket S3 avec **URL publique**

## Installation

```bash
git clone <repo>
cd aws-webapp
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt


# Invoizy

**📄 Invoizy – Make Invoice with Ease**

Invoizy is an open-source invoicing tool...

---

## ⚙️ Configuration

All features are configurable via environment variables. You can store uploaded files locally or in AWS S3, and optionally send emails using SMTP.

See `.env.example` for details:

```
STORAGE_DRIVER=local   # or s3
EMAIL_PROVIDER=smtp    # with SMTP credentials
```


# proj-s3

This project demonstrates the deployment of a **static website on Amazon S3** using Infrastructure as Code (IaC) with Terraform.

---

## 🚀 Project Overview

The objective of this project is to **automate hosting a static website on AWS S3**. It uses Terraform to provision the infrastructure, making deployment repeatable and scalable.

---

## 🛠️ Project Structure

```
proj-s3/
├── main.tf        # Terraform configuration for S3 bucket
├── index.html     # Main HTML file for the website
├── style.css      # CSS styling for the website
```

---

## ✨ Features

* Automated creation of an **S3 bucket** for static website hosting.
* **Public access configuration** for website delivery.
* Hosting of **HTML and CSS files** on S3.
* Terraform code for **repeatable deployments**.
* Easy to customize for your own static website content.

---

## 💼 Prerequisites

* [Terraform](https://www.terraform.io/downloads.html) installed.
* AWS account with permissions to create S3 buckets and manage resources.

---

## ⚡️ Usage

1. **Clone the repository**:

```bash
git clone https://github.com/Saeedullahshaikh/proj-s3.git
cd proj-s3
```

2. **Initialize Terraform**:

```bash
terraform init
```

3. **Plan and Apply Terraform Configuration**:

```bash
terraform plan   # Optional: review what will be created
terraform apply  # Create resources
```

Type `yes` when prompted.

4. **Access the Website**:

* Terraform will output the **S3 bucket website URL**.
* Open the URL in your browser to view the static website.

5. **Modify Content**:

* Update `index.html` or `style.css` to customize your website.
* Re-run `terraform apply` to update the deployed content if necessary.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Notes

* Ensure your **system clock is synced** when using Terraform with AWS (prevents signature errors).
* For advanced setup, you can **enable versioning, logging, or use a custom domain** with Route53.

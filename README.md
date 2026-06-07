# 👕 Garment Catalogue Image Automation Tool

A desktop application that automates garment catalogue image preparation by performing batch image processing, AI-powered background removal, product code generation, logo branding, and image resizing.

Built with **Python**, **Tkinter**, **Pillow**, and **rembg**, the tool transforms a time-consuming manual workflow into a streamlined automated process suitable for wholesalers, manufacturers, distributors, and e-commerce businesses.



\

---

## 🚀 Overview

Preparing garment catalogue images often involves repetitive editing tasks such as:

* Background removal
* Image resizing
* Product code labeling
* Brand logo placement
* File export and organization

When processing hundreds of products, these tasks can consume several hours of manual effort.

This application automates the entire workflow through a simple desktop interface, allowing businesses to generate professional catalogue-ready product images in minutes.

---

## 🎯 Business Problem

Garment wholesalers and catalogue creators frequently need to prepare large volumes of product photographs before distribution to:

* Retail buyers
* Distributors
* Sales representatives
* E-commerce platforms
* Marketing teams

Manual editing introduces:

* Significant labor costs
* Inconsistent image formatting
* Human error
* Slow catalogue production

---

## 💡 Solution

The Garment Catalogue Automation Tool provides a one-click workflow that:

✅ Standardizes image dimensions

✅ Removes backgrounds automatically

✅ Generates sequential product identifiers

✅ Applies company branding

✅ Exports production-ready catalogue images

This reduces repetitive manual work and ensures consistent output quality.

---

## ✨ Features

### 🖼 Batch Image Processing

* Process hundreds of images in a single run
* Automated directory-based workflow
* Consistent image formatting

### 🤖 AI Background Removal

* Powered by `rembg`
* Automatically removes image backgrounds
* Eliminates manual cutout work

### 🔢 Product Code Generation

* Sequential numbering support
* Automatic code incrementation
* Custom prefixes and suffixes

### 🏷 Branding Support

* Overlay company logos
* Maintain brand consistency
* Configurable logo placement

### 📏 Image Standardization

* Custom image dimensions
* Catalogue-ready sizing
* Consistent output across all products

### 🖥 User-Friendly Desktop Interface

* Built with Tkinter
* No coding required
* Folder-based workflow

---

## 🏗 Workflow

```text
Input Images
      │
      ▼
Background Removal
      │
      ▼
Image Resize
      │
      ▼
Product Code Generation
      │
      ▼
Logo Overlay
      │
      ▼
Export Processed Images
```

---

## 🛠 Technology Stack

| Component          | Technology             |
| ------------------ | ---------------------- |
| Language           | Python                 |
| Desktop GUI        | Tkinter                |
| Image Processing   | Pillow (PIL)           |
| Background Removal | rembg                  |
| File Operations    | OS Module              |
| Automation         | Python Workflow Engine |

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/jv0019/Garment_catalog_tool.git
cd Garment_catalog_tool
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python main.py
```

---

## 🚀 Usage

### Step 1: Select Input Directory

Choose the folder containing product images.

### Step 2: Select Output Directory

Choose where processed images will be saved.

### Step 3: Select Logo

Upload a logo image for branding.

### Step 4: Configure Settings

Customize:

* Starting product number
* Prefix text
* Suffix text
* Image width
* Image height

### Step 5: Process Images

Click **Start Processing**.

The application automatically processes every image in the selected folder.

---

## 🔢 Example Product Code

Generated output labels can follow patterns such as:

```text
A4P-25 SIZE-10X14 CODE-BGN
```

Product numbering automatically increments for each processed image.

Example:

```text
A4P-25 SIZE-10X14 CODE-BGN-001
A4P-25 SIZE-10X14 CODE-BGN-002
A4P-25 SIZE-10X14 CODE-BGN-003
```

---

## 📂 Project Structure

```text
garment-catalog-tool/
│
├── main.py
├── requirements.txt
└── README.md
```

---

## 📈 Benefits

### Productivity

* Significantly reduces manual editing time
* Automates repetitive catalogue preparation tasks
* Improves workflow efficiency

### Consistency

* Standardized dimensions
* Uniform branding
* Consistent product labeling

### Scalability

* Process large product batches
* Suitable for wholesale and catalogue production environments

---

## 💼 Use Cases

### Fashion & Apparel

* Garment wholesalers
* Apparel manufacturers
* Fashion distributors

### E-Commerce

* Product image preparation
* Marketplace listing creation
* Catalogue generation

### Marketing & Sales

* Product brochures
* Sales catalogues
* Product presentations

### General Image Automation

* Watermarking
* Batch resizing
* Product labeling
* Brand asset management

---

## 🚀 Future Enhancements

Planned improvements:

* [ ] Drag-and-drop image upload
* [ ] Real-time processing progress bar
* [ ] Multiple export presets
* [ ] Standalone executable build
* [ ] Batch watermark templates
* [ ] Cloud storage integration
* [ ] QR code generation
* [ ] Multi-logo support
* [ ] Export history tracking

---

## 📜 License

MIT License

---

## 👤 Author

**Jivitesh Sachdev**

Software Development • Business Process Automation • Python Applications

GitHub: https://github.com/jv0019

---

### Keywords

Python • Desktop Application • Tkinter • Image Processing • Computer Vision • Business Automation • Garment Industry • Product Catalogue Generation • Batch Processing • Workflow Automation

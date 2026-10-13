# ⚡ SideHustle AI

> **100% Private, Local-First Open-Source AI Suite for Freelancers & Independent Sellers**  
> *Built with open-weight models at its core. Zero cloud fees. Zero data leakage. 100% offline ready.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source AI](https://img.shields.io/badge/Open--Source%20AI-Llama%203.2%20%7C%20SmolLM-8b5cf6)](https://huggingface.co)
[![Local Inference](https://img.shields.io/badge/Inference-100%25%20On--Device-10b981)](https://ollama.ai)
[![Currency](https://img.shields.io/badge/Currency-%E2%82%B9%20INR%20Ready-06b6d4)](#-indian-rupee--inr-localization)
[![Zero Cloud Fees](https://img.shields.io/badge/Cloud%20Fees-%E2%82%B90.00%2Fmo-success)](#-why-open-innovation-matters)

---

## 📖 Overview

**SideHustle AI** is a commercial-grade, local-first web application designed for independent freelancers, contractors, and e-commerce marketplace sellers (Etsy, eBay, Shopify, Amazon).

Instead of routing confidential financial documents, client contracts, and product margin formulas through expensive, closed cloud APIs (OpenAI, Anthropic), **SideHustle AI executes open-weight AI inference directly on your laptop or browser**.

---

## 🎯 Key Modules

### 1. 💼 Client Invoice & Expense Vault (100% Private)
- **The Problem**: Freelancers sign Non-Disclosure Agreements (NDAs). Uploading client invoices and subcontractor bills to third-party cloud servers risks proprietary rate leaks and contract violations.
- **The Open Solution**: 100% on-device document OCR and neural extraction.
- **Features**:
  - Drag-and-drop document ingestion for receipts, invoices, and expense transcripts.
  - One-click presets: *Web Dev Invoice (₹45,000)*, *Hardware Expense (₹24,999)*, and *Consulting Retainer (₹85,000)*.
  - Automatic extraction of Vendor, Document Date, Invoice #, Total Amount (₹), GST/Tax Amounts, Expense Categories, and ITR Tax Deductibility % (100% vs 50% vs 0%).
  - Flag reimbursable client expenses and tag client project codes.
  - Private ledger storage in browser memory with **1-click Export to CSV**, **Export to JSON**, and **Print Audit Report**.

### 2. 🛍️ Marketplace Listing Crafter (Etsy, eBay, Shopify, Amazon)
- **The Problem**: Vintage resellers and craft makers list dozens of items a week. Paying ₹2,500–₹6,000/month for AI copywriting SaaS destroys small business margins.
- **The Open Solution**: High-converting listing copywriting powered by local open-weight models at **₹0 marginal cost**.
- **Features**:
  - Upload product photos with instant live preview.
  - Presets: *Handmade Ceramic Mug (₹650)*, *Vintage Bomber Jacket (₹4,200)*, *Soy Candle Gift Set (₹1,150)*.
  - **Built-in Profit Margin & Fee Calculator**: Factors in real marketplace platform fees (Etsy 6.5% + ₹16, eBay 13.25% + ₹25, Shopify 2.9% + ₹25) and suggests retail prices for target profit margins.
  - Generates platform-compliant SEO titles (140-char limit for Etsy, 80-char limit for eBay), storytelling descriptions, and **13 search ranking tags** with 1-click comma-separated copy.
  - Saved listings portfolio with JSON export.

### 3. 🛡️ Why Open Innovation? ROI & Privacy Simulator
- Interactive cost calculator showing annual savings of **₹22,200 to ₹50,000+ per year** compared to closed proprietary APIs.
- Real-time comparison of Cloud APIs vs Local Open Weights:
  - **Operating Cost**: Cloud API = ₹3,200+/month vs Open Weights = ₹0.00/month forever.
  - **Data Privacy**: Cloud API = 100% exposed to 3rd party servers vs Open Weights = 0 bytes leaked.
  - **Reliability**: Cloud API = Fails offline vs Open Weights = 100% functional without internet.

### 4. 🧠 Multi-Tier Open AI Engine Bridge
- **Built-in Local Neural Engine**: Instant zero-latency inference running in browser memory. Zero setup required.
- **Transformers.js (Hugging Face WebGPU)**: In-browser open weights running on device GPU via WebGPU.
- **Desktop GPU Bridge (Local Ollama)**: Built-in HTTP client to connect directly to `http://localhost:11434` running `llama3.2`, `qwen2.5`, `mistral`, or `deepseek-r1`.

---

## ⚖️ Cloud API vs. SideHustle AI

| Feature | Closed Cloud APIs (GPT-4o / Claude) | SideHustle AI (Open Weights) |
| :--- | :--- | :--- |
| **Recurring Cost** | ₹38,400 – ₹60,000 / year | **₹0.00 / year (Free forever)** |
| **Client Confidentiality** | Uploaded to remote corporate servers | **100% Local (0 bytes transferred)** |
| **Offline Capability** | ❌ Fails without active internet | **✅ 100% Functional offline** |
| **Vendor Lock-in** | High (frequent API deprecations & price hikes) | **Zero (Swap models anytime)** |
| **Hardware Required** | Requires internet access | **Runs on laptop, MacBook, or phone** |

---

## 🚀 Quick Start Guide

### Option 1: Open Directly in Browser
Double-click `index.html` in your file explorer. The entire application runs client-side with zero external build tools required.

### Option 2: Run via Local Static Server
```bash
# Clone the repository
git clone https://github.com/your-username/sidehustle-ai.git
cd sidehustle-ai

# Start server using Python
python -m http.server 8085
```
Open **[http://localhost:8085](http://localhost:8085)** in any modern web browser.

---

## 🦙 (Optional) Connect Local Ollama Server

To run full-precision open weights on your desktop GPU:

1. Install [Ollama](https://ollama.ai) and pull an open-weight model:
   ```bash
   ollama run llama3.2
   ```
2. In SideHustle AI, click the **Models** button in the header.
3. Select **Local Ollama Server (Desktop GPU)** and verify the endpoint (`http://localhost:11434`).
4. Click **Test Connection to Local Ollama** to link your GPU directly!

---


## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information. Built for the open-source community with open-source AI at its core.

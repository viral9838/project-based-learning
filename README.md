# Azure Document Intelligence Project

A Python application that leverages Azure AI Document Intelligence to extract structured data from documents including invoices, receipts, forms, and general documents.

## Features

- **Text Extraction**: Extract printed and handwritten text from documents
- **Table Detection**: Identify and extract tabular data
- **Key-Value Pair Extraction**: Extract form fields and their values
- **Pre-built Models**: Support for invoices, receipts, ID documents, and business cards
- **Custom Models**: Framework for training custom extraction models

## Prerequisites

- Python 3.8+
- Azure subscription
- Azure AI Document Intelligence resource

## Setup

### 1. Create Azure Resource

1. Go to [Azure Portal](https://portal.azure.com)
2. Create a new **Document Intelligence** resource
3. Copy the **Endpoint** and **Key** from the Keys and Endpoint section

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# project-based-learning

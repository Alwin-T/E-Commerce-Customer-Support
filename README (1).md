# Intelligent Customer Interaction Management System (ICIMS) – E-Commerce Voice Agent

## Overview
This project implements an **AI-powered voice agent** for e-commerce customer support using **smallest.ai**.  
The agent assists customers with product inquiries, order tracking, returns, FAQs, and escalation to human agents, delivering quick and accurate responses.

---

## Features
- **Voice Interaction**: Natural conversation via phone or web chat.  
- **Order Tracking**: Retrieve order status when given an Order ID.  
- **Product Assistance**: Provide details about products, pricing, and availability.  
- **Returns & Refunds**: Explain policies and guide customers through the process.  
- **Escalation**: Transfer complex queries to a human representative.  
- **Search Integration (Optional)**: Connect to external search APIs for broader information retrieval.  

---

## Tech Stack
- **Platform**: smallest.ai  
- **Tools**:  
  - Python (for data preparation and file processing)  
  - ReportLab (for generating formatted documents)  

---

## Project Structure
📂 icims-voice-agent  
 ├── 📂 data  
 │    ├── output_first150.csv              # Sample order and product data  
 │    ├── ecommerce_faq.pdf                 # Frequently asked questions  
 │    └── about_agent.txt                   # Agent overview  
 ├── 📂 scripts  
 │    ├── csv_trim.py                       # Extract a subset of data  
 │    ├── replace_order_ids.py              # Assign unique anonymized order IDs  
 ├── README.md  
 └── requirements.txt  

---

## Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/icims-voice-agent.git
cd icims-voice-agent
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Configure smallest.ai Agent
- Upload relevant data files.  
- Set system prompt to handle customer interactions and order tracking.  
- Map API calls if enabling web search or external data lookups.  

---

## Usage
- Customers interact with the agent through voice or chat.  
- The agent responds to questions, tracks orders, and handles return/refund processes.  
- For complex issues, the agent escalates the request to a human.  

---

## Example Conversation
```vbnet
Customer: Hi, I want to track my order.
Agent: Sure! Please provide your Order ID.
Customer: 457
Agent: Your order #457 is in transit and will arrive by Tuesday.
```

---

## Future Enhancements
- Live database integration for real-time order and inventory updates.  
- Advanced analytics dashboard for conversation insights.  
- Multi-language support for global reach.  

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

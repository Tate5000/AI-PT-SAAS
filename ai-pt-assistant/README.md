# AI Communication & Scheduling Assistant for David Craft PT

## 🚀 Overview

This project automates patient communication, lead intake, appointment scheduling, and superbill generation for physical therapy clinics, starting with David Craft PT.

### 🎯 MVP Goal

Automate 80% of incoming communication and admin tasks in 2–3 weeks.

---

## 🧩 Features

### 1. Centralized Communication Bot
- Auto-replies to SMS, email, and web form leads
- GPT-powered responses with fallback to human
- Calendar link + intake prompts

### 2. Smart Scheduling
- API integration with Calendly/TidyCal
- Handles bookings + reschedules via SMS/email
- AI suggests times based on availability

### 3. Superbill Generator
- Form input → GPT → PDF output
- Sends link to patient via SMS/email

### 4. Lead Follow-Up Automation
- Missed call replies
- Form fill follow-up
- No-show nudges

### 5. Admin Dashboard (Optional)
- Inbox view
- Superbill generation
- Notes and file uploads

---

## 🛠️ Tech Stack

- **AI**: GPT-4 (OpenAI) prompt chaining
- **Messaging**: Twilio or OpenPhone API
- **Scheduler**: Calendly/TidyCal (API access)
- **Backend**: Node.js + Firebase or Supabase
- **Automation**: Zapier/Make or custom cron jobs
- **Frontend (Optional)**: Next.js + Tailwind
- **PDF**: Puppeteer or React-PDF

---

## 🗂 Directory Structure

See project layout [above](#project-directory-structure).

---

## ✅ Phase 1 Deliverables

| Feature             | Outcome                                     |
|---------------------|---------------------------------------------|
| SMS/Email Bot       | Handles basic replies & leads automatically |
| Scheduling          | Self-serve booking/rescheduling             |
| Superbill Tool      | One-click doc creation + delivery           |
| Lead Follow-Up      | No more dropped leads                       |
| Dashboard (Optional)| Unified view of ops                         |

---

## 🧪 Local Setup

```bash
git clone https://github.com/your-org/ai-pt-assistant
cd ai-pt-assistant
npm install
cp .env.example .env



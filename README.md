# 🏥 DivyaShakti AI Health Assistant

An AI-powered Doctor Appointment Booking System built at HackDays 2026 Hackathon.

**Team: Code Ninjas | Track: HealthCare**
Organized by HackBase Society × Major League Hacking (MLH)

---

## 📖 Abstract

The DivyaShakti AI Health Assistant is an AI-driven appointment scheduling system designed to automate and streamline the patient booking process in small clinics and healthcare centers. By leveraging workflow automation and conversational AI, the system eliminates manual intervention, reduces operational inefficiencies, and enhances patient experience.

---

## 📌 Problem Statement

Despite advancements in healthcare technology, many small clinics still rely on traditional appointment booking methods such as phone calls or in-person scheduling. These approaches suffer from:

- Inefficient time management
- Increased likelihood of human error
- Lack of real-time availability tracking
- Poor patient experience due to delays

---

## ✅ Our Solution

An automated AI-powered assistant that facilitates seamless appointment booking through a conversational interface on Telegram. The system:

- Collects patient information interactively
- Provides real-time slot availability
- Automatically confirms appointments
- Works 24/7 without human intervention

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation engine |
| Telegram Bot API | Patient chat interface |
| Google Gemini API | AI responses + symptom analysis |
| Google Calendar API | Real-time slot scheduling |
| Google Cloud | Infrastructure |

---

## ✨ Key Features

- Fully automated appointment scheduling
- Real-time slot management via Google Calendar
- AI-based conversational interface using Gemini API
- Platform-independent access via Telegram
- 24/7 instant booking without human intervention
- Collects Name, Phone, Email and Symptoms

---

## 🔄 How It Works

```
User sends message on Telegram
        ↓
n8n Webhook Trigger receives message
        ↓
AI Agent processes using Google Gemini API
        ↓
Google Calendar checks available slots
        ↓
Bot collects patient details step by step
        ↓
Appointment booked and confirmed instantly
```

---

## ⚙️ System Architecture

The system follows a modular and event-driven architecture:

**User Interaction Layer**
Patients initiate communication via Telegram

**Processing Layer**
AI Agent interprets user inputs using Google Gemini API
n8n orchestrates the entire workflow automation

**Scheduling Logic**
Validates date and time inputs
Retrieves available appointment slots from Google Calendar

**Response Layer**
Confirms bookings and communicates with user in real time

---

## 📊 Impact

- Enables digital transformation for small healthcare providers
- Reduces administrative workload significantly
- Improves scheduling accuracy and efficiency
- Enhances patient satisfaction and accessibility

---

## 🔮 Future Scope

- Integration with WhatsApp and web-based interfaces
- SMS and Email reminder notifications
- Dedicated dashboard for clinic management
- Predictive analytics for patient flow optimization
- EHR (Electronic Health Record) integration

---

## 🏆 Hackathon Details

| Field | Details |
|-------|---------|
| Event | HackDays 2026 |
| Organizer | HackBase Society × GCET |
| Partner | Major League Hacking (MLH) |
| Date | 11th April 2026 |
| Track | HealthCare |
| Round | Qualified Online + Offline Final Round |
| Team | Code Ninjas |

---

## 👩‍💻 Team Code Ninjas

| Name | Role |
|------|------|
| Shivani Singh | Team Leader & Developer |
| Shraddha Singh | Developer |
| Vanshika Maurya | Developer |
| Yash Srivastava | Developer |

### My Contribution

- Served as Team Leader for team of 4
- Created complete project presentation (PPT)
- Tested and demonstrated bot via Telegram chat
- Participated in n8n workflow development
- Coordinated team tasks and deliverables
- Delivered final presentation to judges

---

## 🔗 Project Link

[GitHub Repository](https://github.com/Shiivani05/DivyaShakti-AI-Health-Assistant)

---

## 📌 Conclusion

The DivyaShakti AI Health Assistant demonstrates how AI and automation can effectively address inefficiencies in traditional healthcare systems. The solution is cost-effective, scalable, and adaptable — suitable for widespread adoption in small and medium-scale healthcare facilities.

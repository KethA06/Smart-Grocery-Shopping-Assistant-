Smart Grocery Shopping Assistant

An AI-based mini project developed as part of AI Techniques and Agent Technology to help users manage grocery shopping more efficiently with smart suggestions, healthier alternatives, and expiry reminders.

📌 Project Overview

The Smart Grocery Shopping Assistant is designed to act as a digital helper for everyday grocery shopping.
It analyzes user purchase history to:

Predict frequently used or forgotten items

Suggest healthier alternatives

Track expiry dates and reduce food waste

This system improves shopping efficiency, saves time, and promotes healthier choices.

🎯 Objectives

Create and manage grocery lists easily

Predict missing or frequently purchased items

Suggest healthier food alternatives

Remind users about items close to expiry

Personalize shopping using purchase history

Reduce food waste and user effort

⚙️ Features

✅ User Login

📝 Grocery List Management (Add / Edit / Delete)

🤖 Smart Item Suggestions based on past purchases

🥗 Healthier Alternative Recommendations

⏰ Expiry Date Tracking & Alerts

💾 Purchase History Storage

🧠 AI Technique Used

Rule-Based Reasoning

Forgotten items (bought 7+ days ago)

Frequently purchased items (4 out of last 5 trips)

Healthier alternative mapping (e.g., White bread → Brown bread)

🏗️ System Architecture

Frontend: React

Backend: FastAPI

Data Storage: JSON

Validation: Pydantic

📋 Functional Requirements

Secure user login

Grocery list CRUD operations

Smart suggestions and reminders

Healthier food recommendations

Persistent data storage

📈 Non-Functional Requirements

Simple and user-friendly UI

Fast API responses

Secure data handling

Reliable and maintainable code

Browser compatibility

🚀 How to Run the Project
# Backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
npm install
npm run dev

📊 Output

Smart grocery list with AI suggestions

Expiry reminders for purchased items

Healthier alternative recommendations

📌 Conclusion

This mini project demonstrates how AI techniques like rule-based reasoning can be applied to solve real-life problems.
The Smart Grocery Shopping Assistant helps users shop smarter, stay organized, and reduce food waste using simple yet effective AI logic.

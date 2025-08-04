# 📚 BookIQ – AI-Powered Book Recommendations

Welcome to [utkarsh1234456.github.io](https://utkarsh1234456.github.io/), the homepage for **BookIQ** – an intelligent book recommendation platform powered by IBM Watson Assistant.

## 🚀 Features

- 🔍 AI chatbot for personalized book suggestions  
- 📖 Recommendations by genre, author, and mood  
- 📱 Responsive and modern user interface  
- 💬 Watson Assistant integration for real-time interaction  

## 🛠️ Technologies Used

- HTML5 + Tailwind CSS  
- JavaScript (for Watson Assistant embedding)  
- IBM Watson Assistant (Chatbot Integration)  
- Hosted on GitHub Pages  

## 🤖 Watson Assistant Integration

The chatbot is embedded using the following configuration:

```js
window.watsonAssistantChatOptions = {
  integrationID: "38230aea-4bf4-4cc8-9ad2-6435d37c58ee",
  region: "eu-de",
  serviceInstanceID: "ea42bf7b-c62b-45f4-b20f-5a1eeb72148b",
  onLoad: async (instance) => { await instance.render(); }
};

# **MyJourneyAI \- AI Travel Planner**

**MyJourneyAI** is a dynamic, single-page web application designed to help users explore travel destinations across India and generate personalized itineraries using the power of Google's Gemini AI. It's built as a single, self-contained HTML file, requiring no complex setup or installation.

## **Key Features**

MyJourneyAI is built around two core modules designed for seamless travel planning and discovery, enhanced by a suite of intelligent AI assistants.

### **Core Modules**

* **Interactive Exploration Guide**: A rich, visual interface to discover Indian states. Dive deep into destinations with stunning imagery, detailed overviews, must-see attractions, and local insights on cuisine and activities.  
* **AI-Powered Itinerary Planner**: Move beyond static plans. Input your unique travel preferences—duration, budget, interests, and pace—and let the AI construct a personalized, day-by-day itinerary that perfectly matches your travel style.

### **Intelligent Travel Assistants**

Once your itinerary is crafted, unlock a deeper layer of planning with specialized AI tools:

* **✨ On-Demand AI Concierge**: Have a specific question? While exploring a state, use the built-in concierge to get instant answers about anything from photography spots to local transportation.  
* **🔊 Audio Itinerary Guide**: Listen to your daily plans on the go. The Text-to-Speech feature turns your itinerary into an audio guide, perfect for reviewing your schedule without looking at a screen.  
* **Automated Briefing Packs**: Generate essential travel documents with a single click:  
  * **Personalized Packing List**: Get a checklist of what to pack, tailored to your trip's destinations and activities.  
  * **Cultural & Safety Guide**: Receive crucial advice on local etiquette, useful phrases, and safety tips for the regions you'll be visiting.  
  * **Curated Foodie Guide**: Discover the must-try dishes and best places to eat with a culinary guide created just for your journey.

## **Technology Stack**

* **Frontend**: Vanilla HTML, CSS, and JavaScript.  
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) for a modern, responsive design.  
* **AI & Machine Learning**:  
  * **Google Gemini API (gemini-2.5-flash-preview-05-20)**: Powers the core itinerary generation, AI assistants, and the concierge feature.  
  * **Google Gemini API (gemini-2.5-flash-preview-tts)**: Used for the Text-to-Speech audio guide feature.

## **How to Use**

This application is designed for simplicity. No build tools, package managers, or servers are required.

1. **Download the File**: Save the index.html file to your local machine.  
2. **Open in Browser**: Double-click the index.html file to open it in any modern web browser (like Chrome, Firefox, or Edge).

The application is now ready to use\!

## **Important Note**

This project uses the Google Gemini API, which requires an API key to function. The apiKey constant in the index.html file has been left intentionally blank. To make the AI features work, you must obtain your own API key from [Google AI Studio](https://aistudio.google.com/) and place it in the designated spot in the code.

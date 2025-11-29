---
title: "🥏SquadUp"
excerpt: "<img src='/images/visual selection.png' style='cursor: crosshair;'>"
collection: portfolio
tags: 
  - Web app
  - Lovable 
  - React
  - TypeScript
  - OAuth2 authentication
  - PostgreSQL DB
  - Tailwind CSS
  - Full-stack
  - Gemini
---

<style>
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 50px;
  }
  .app-text {
    font-size: 18px;
    margin-right: 15px;
  }
  .app-button {
    background: url('/images/kano.png') no-repeat center center;
    background-size: cover;
    width: 200px;  /* Adjusted size */
    height: 50px;  /* Adjusted size */
    border: none;
    border-radius: 25px;
    cursor: pointer;
    box-shadow: 0 4px #999;  /* 3D shadow effect */
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .app-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px #666;
  }
  .app-button:active {
    transform: translateY(2px);
    box-shadow: 0 2px #333;
  }
</style>

<div class="container" style="margin-top: -25px;">
  <div class="app-text"> <h2> Access the web app ↪️</h2> </div>
  <a href="https://sports-on-the-go.lovable.app/" target="_blank">
    <button class="app-button"></button>
  </a>
</div>

* Architected and deployed a **full-stack cloud-native web app** using **React**, **TypeScript**, **Supabase (PostgreSQL, Auth, Edge Functions)**, and **Tailwind CSS**.

<img src="/images/web_landing.png" style="cursor: crosshair;">

* Deployed a **Gemini AI chatbot** for personalized game recommendations and natural-language match search.

<img src="/images/Gemini chat.png" style="cursor: crosshair;">

* Built an interactive map experience using Leaflet and OpenStreetMap APIs to visualize nearby pickup games in real time, leveraging geo-queries and real-time subscriptions for dynamic, user-centric experiences.

<img src="/images/web_map.png" style="cursor: crosshair;">

* Optimized frontend performance and UX with TanStack Query, React Hook Form, and Zod validation, improving data consistency and client-side responsiveness by **40%**.

* Engineered secure backend workflows with Row Level Security (RLS), serverless Deno edge functions, and API integrations for geocoding and content moderation—implementing best practices for data privacy, authentication, and multi-tenant access control, aligning with **Azure DevOps principles**.

<div class="flexcontainer">
  <div>
        <span>✦ <strong>Code:</strong></span> <a href="https://github.com/SudarshanaSRao/sports-on-the-go-4c575e84" target="_blank" onclick="trackOutboundLink(this);">
      <img class="pulse" height="30px" src="/images/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="80px">
    </a>
  </div>
</div>

<style>
  .flexcontainer {
    display: flex;
    align-items: center;
    margin-bottom: 20px; /* Adjust the value as needed */  
  }
@keyframes pulse {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
  100% {
    transform: scale(1);
  }
}
.pulse {
  animation: pulse 2s infinite ease-in-out;
}
</style>

# analyze-your-meeting-reactjs-nestjs
Have a tool that can be included in your every google meet or zoom meeting and it will help you analyze the on going conversation and help you keep going or maintain the direction of the talk. It can give you real-time Keywords, Situations, Challenges, Risks, Impacts and Solutions. 



## AI Meeting Insights App (TranscriptGpt)

## Table of Contents

1. [Introduction](#1-introduction)
2. [Project Overview](#2-project-overview)
3. [Getting Started](#3-getting-started)
4. [Code Structure](#4-code-structure)
5. [Dependencies](#5-dependencies)
6. [Deployment](#7-deployment)
7. [Usage](#8-usage)


## 1. Introduction

Welcome to the documentation for the AI Meeting Insights App, a simple and refactored project designed to manage your meetings efficiently. This document provides an overview of the project, its code structure, refactoring details and usage instructions.

## 2. Project Overview

Have a tool that can be included in your every google meet or zoom meeting and it will help you analyze the on going conversation and help you keep going or maintain the direction of the talk. It can give you real-time Keywords, Situations, Challenges, Risks, Impacts and Solutions. 

## 3. Getting Started

To get started with the TranscriptGpt App, follow these steps:

### Prerequisites

Make sure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Safari)
- An internet connection (for fetching external dependencies)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:Creolestudios/analyze-your-meeting-reactjs-nestjs.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd analyze-your-meeting-reactjs-nestjs
   ```

3. **Client and Server Setup**

   * Create and Add credentials in .env file 

   ```
   PORT=

   BASE_URL=

   OPEN_AI_KEY=

   INTERVAL=2=

   ```

   ## Client Setup

   ```
   npm install 

   npm start 

   ```


   ## Server Setup


   ```
   npm install 

   npm run start:dev

   ```




## 4. Code Structure

The project follows a modular and organized structure to enhance readability, maintainability, and scalability. Key components include:

- **ReactJs** The main structure of the web page designed using React Framework.
- **NodeJs** Backend Logic written in nodejs, Logic for handling user interactions, getting transcript , and giving summary as Situations, Challenges, Risks, Impacts and Solutions.
- **HnsWlib Vector DB** Storing transcript in db to efficiently get resault based on similarity search Algorithm. 
- **OpenAI** Using OpenAI api key to get summary of Situations, Challenges, Risks, Impacts and Solutions from transcript.

## 5. Dependencies

- **LangChain** NLP based library which provides easy integration of openai with our data 
- **OpenAI** Provides different text based models like gpt-3.5,gpt-4,text-ada-embedding



## 6. Deployment

The TranscriptGpt App is deployed and accessible online. You can use the following link to access the application: [AI Meeting App](https://www.creole.tech/transcriptgpt/)

## 7. Usage

1. **Adding a Transcript:**
   - Add transcript manually or fetch from meeting

2. **Selecting Time Interval:**
   - Select/Clieck on time interval for which you want to get summary for.

3. **Selecting Keywords from Transcript:**
   - Click the "submit" button after selecting Keywords.

4. **Get Situations:**
   - Click the "submit" button after selecting situations to get Challenges.

5. **Get Challenges:**
   - Click the "submit" button after selecting Challenges to get Risk.

6. **Get Risk:**
   - Click the "submit" button after selecting Risks to get Impacts and Solutions.


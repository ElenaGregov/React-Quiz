# 🧠 React Quiz

**React Quiz** is a single-page quiz application built with React. It loads questions from a mock backend using JSON Server and allows users to test their knowledge in a simple and interactive format.

## 📌 Project Overview

This project was developed during a web development course to practice working with React components, hooks, and basic API integration using a local JSON Server.

## 🚀 Features

- Load quiz questions from a mock REST API
- Display one question at a time with multiple answers
- Track user score and show results
- Reset quiz functionality
- Responsive UI for desktop and mobile

## 🛠️ Tech Stack

- [React](https://reactjs.org/) (via Create React App)
- [JSON Server](https://github.com/typicode/json-server)
- Testing libraries:  
  - `@testing-library/react`  
  - `@testing-library/jest-dom`  
  - `@testing-library/user-event`

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ElenaGregov/react-quiz.git
cd react-quiz

## 🗄️ JSON Server Setup

This project uses [JSON Server](https://github.com/typicode/json-server) as a mock backend to serve quiz data.

### 🔧 How to Start JSON Server

If you're using `npm` scripts (already set in `package.json`), simply run:

```bash
npm run server

## 🗄️ JSON Server Setup

This project uses [JSON Server](https://github.com/typicode/json-server) as a mock backend to serve quiz data.

### 🔧 How to Start JSON Server

If you're using `npm` scripts (already set in `package.json`), simply run:

```bash
npm run server

If you want to run it manually:

```bash
npx json-server --watch data/questions.json --port 9000


🧠 What I Learned

- Building interactive components using React hooks

- Managing local state and side effects

- Integrating a mock REST API using JSON Server

- Basic test writing with React Testing Library



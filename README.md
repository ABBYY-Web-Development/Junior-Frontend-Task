# 📝 Test Task for Junior Frontend Developer

## 🎯 Goal
We want to evaluate your ability to create a responsive, well-structured web page using modern frontend technologies. The task focuses on adaptive layout, semantic HTML, and SCSS styling. Since we use **Next.js** in our projects, we also want to see how you work with it.

## 📌 Task Description
You need to develop a simple **blog post listing page** using Next.js. 
The page should display a list of blog posts with images, titles, descriptions, dates, 
"Read more" links, view counts, reading time estimations,  and optional tags. 
The data should be fetched from a fake API using a library like `json-server` or `msw` (Mock Service Worker).

Additionally, you should use **a free blog design from [Figma Community](https://www.figma.com/community)** as a reference. 
Choose any **free** [blog UI kit](https://www.figma.com/community/search?resource_type=mixed&sort_by=relevancy&query=blog&editor_type=figma&price=free&creators=all)
and include the link to it in your README file.

**Do not use CSS/JS UI libraries** (e.g., Bootstrap, Material UI, Tailwind). The styling should be implemented using SCSS from scratch.

### 🔹 Requirements

#### **Page Layout**
✅ Implement a **responsive** blog post listing page.  
✅ Use **SCSS** for styling.  
✅ Do not use CSS/JS UI libraries.  
✅ Use a **grid-based** layout that adapts to different screen sizes.  
✅ Ensure accessibility (e.g., semantic HTML, proper use of alt attributes for images).  
✅ Use a **mobile-first approach** in your styles.  
✅ Use **any free blog [design](https://www.figma.com/community/search?resource_type=mixed&sort_by=relevancy&query=blog&editor_type=figma&price=free&creators=all)**
from [**Figma Community**](https://www.figma.com/community) and include the link in `README.md`.

#### **Functionality**
✅ Fetch blog post data from a mock API. You can use:  
   - `json-server` or `msw` (Mock Service Worker).  
   - [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts) for blog post titles and descriptions.  
   - [Lorem Picsum](https://picsum.photos/) for random images.  

✅ Display each blog post with:
   - **Image**
   - **Title**
   - **Short description**
   - **"Read more" button**
   - **Publication date**
   - **View count (can be static, but you may optionally implement dynamic functionality)**
   - **Estimated reading time (can be static, but you may optionally calculate it dynamically)**
   - **Tags** (optional)  

✅ Clicking "Read more" should navigate to a **detailed post page** (`/posts/[id]`).  

#### **Code Quality:**  
✅ Use **ESLint and Prettier** to ensure clean and consistent code formatting.  
✅ Write clear, maintainable, and structured code.  

#### **Tech Stack:**  
✅ **Next.js** (for routing and data fetching).  
✅ **React** (functional components, hooks).  
✅ **SCSS** (organized and maintainable styles).  
✅ **TypeScript** (optional, but preferred).  
✅ **Git** (push your solution to a public GitHub repository).  

---

## 🌟 Bonus (Optional, but appreciated)
⭐ Implement **a dark mode toggle** using React state.  
⭐ Add **simple animations** (e.g., fade-in effects with CSS transitions).  
⭐ Make the view counter dynamic, increasing when a post is opened.  
⭐ Dynamically calculate the estimated reading time based on word count (e.g., assuming 200 words per minute).

---

## 📤 Submission Guidelines
1. Push your code to a **public GitHub repository**.
2. Include a **`README.md`** with:
   - **Setup instructions**
   - **Link to the Figma design used**
   - **Brief explanation of your approach**

---

## ✅ Evaluation Criteria
🔹 **Code structure and readability**  
🔹 **Mobile responsiveness and UI quality**  
🔹 **Accessibility and performance considerations**  
🔹 **Bonus features implementation** (if any)  

---

Good luck! 🚀

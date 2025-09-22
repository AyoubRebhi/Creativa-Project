# 🎨 CreaTiva  

In the context of globalization, the sale of goods and services in the field of arts represents an opportunity for all users to develop their talents.  

**CreaTiva** is an application that allows users to participate in art courses and enables artists to share their creations.  
It is a space where learning and discovery come together, offering everyone the possibility to explore their artistic potential and discover new talents.  

---

## 📂 Repositories  

- **Web Application** 👉 [CreaTiva-Web](https://github.com/AyoubRebhi/Creativa_WEB)  
- **Desktop Application** 👉 [CreaTiva-Desktop](https://github.com/AyoubRebhi/Creativa)  

---

## 🚀 Features  

1. **Showcase Artworks**  
   - Tools for artists to display their creations more visibly and reach a broader audience.  

2. **Community Building**  
   - Virtual communities where artists and art enthusiasts can interact, exchange ideas, and collaborate on artistic projects.  

3. **Job & Collaboration Opportunities**  
   - Connecting artists with commissions, projects, or potential collaborations.  

---

## 💻 Platforms  

- 🌐 **CreaTiva Web**: Accessible via browser for learning, sharing, and discovering art.  
- 🖥️ **CreaTiva Desktop**: A dedicated desktop app for enhanced creativity and collaboration.  

---

## 📊 Architecture Overview  

```mermaid
flowchart TD
    User[User] -->|UI/UX| Web[🌐 CreaTiva Web App]
    User -->|UI/UX| Desktop[🖥️ CreaTiva Desktop App]

    Web --> Backend[Backend API]
    Desktop --> Backend

    Backend --> DB[(Database)]
    Backend --> Community[Community Services]
    Backend --> Jobs[Job/Collaboration Module]

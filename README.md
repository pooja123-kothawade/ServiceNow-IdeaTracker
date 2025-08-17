```markdown
# 💡 Idea Tracker (ServiceNow Application)

A simple low-code application built in **ServiceNow Creator Studio** to track and manage ideas.  
The app allows users to submit new ideas, upvote existing ones, and enables reviewers to approve or reject ideas.  
It’s designed as a lightweight **Idea Management System** that can be extended for organizational use.

---

## 🚀 Features

- **Submit Idea**: Users can create new ideas with title, description, and category.  
- **Track Status**: Each idea has a workflow status → New, Under Review, Approved, Rejected, Implemented.  
- **Upvote**: Users can upvote ideas to promote popular suggestions.  
- **Reviewer Actions**: Special buttons (Approve/Reject) available for reviewers.  
- **Notifications**: Automated notifications using Flow Designer.  
- **List Views**: "All Ideas" view showing Title, Status, Votes, Submitted By.

---

## 🛠️ Tech Stack

- **Platform**: ServiceNow (Creator Studio / App Engine Studio)  
- **Backend Logic**: GlideScript (UI Actions)  
- **Workflow Automation**: Flow Designer  
- **UI Components**: Custom tables, forms, list views  

---

## 📸 Screenshots

### Submit Idea Form


### All Ideas List


### Idea Form with Upvote Button


## 📂 
```

## 🎯 How It Works

1. **Submit an idea** via the "Submit Idea" module.  
2. The idea is stored in the `Idea Tracker Request` table with `New` status.  
3. Users can **upvote** ideas using the Upvote button (increments votes).  
4. Reviewers can **approve/reject** ideas with custom UI Actions.  
5. Notifications are triggered on idea submission or status change.  
6. "All Ideas" list view shows sortable list by votes/status.

---

## 📽️ Demo Video (Optional)

[▶ Watch Demo](https://youtu.be/your-demo-link)  


---

## 🔗 Links

- **GitHub Repo**: [Idea Tracker](https://github.com/pooja123-kothawade/ServiceNow-IdeaTracker)  

---

## 📌 Future Enhancements

- Prevent duplicate voting by tracking user votes.  
- Add comments/discussion on ideas.  
- Service Portal page for end-user submissions.  
- Analytics dashboard for top-voted ideas.

---

## 👩‍💻 Author

**Pooja Kothawade**  
- GitHub: [@pooja123-kothawade](https://github.com/pooja123-kothawade)  
- LinkedIn: [Pooja Kothawade](https://www.linkedin.com/in/pooja-kothawade-techpro/)  
```

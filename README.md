## GitHub Static Page Challenge  

### **Objective**  
Create a **static webpage** summarizing what you learned from the Hack Workshop! You will first **clone this repository**, then create your **own repository** to deploy your work using **GitHub Pages**.  

### **Steps to Complete the Challenge**  

#### **1️⃣ Clone this repository (DO NOT EDIT THIS REPO!)**  
- Open your terminal and run:  
  ```bash
  git clone https://github.com/TheEmeraldHack/GitHub-Static-Page-Challenge.git
  ```  
- This creates a local copy of the project on your computer.  
- **Do not push changes to this repo!** You will create your own repo in the next step.  

#### **2️⃣ Create your own GitHub repository**  
- Go to [GitHub](https://github.com/) and click **New Repository**.  
- Name it something like `my-hackathon-page`.  
- **Do NOT initialize it with a README, license, or .gitignore.**  
- Click **Create Repository** and copy the repository URL.  

#### **3️⃣ Connect your local project to your new repository**  
In your terminal, navigate to the cloned repo folder:  
```bash
cd GitHub-Static-Page-Challenge
```  
Then, run the following commands to link your project to your new GitHub repo:  
```bash
git remote remove origin  # Remove the original repository link
git remote add origin https://github.com/YOUR-USERNAME/my-hackathon-page.git
git branch -M main  # Ensure you're on the main branch
git push -u origin main  # Push your code to your own repository
```

#### **4️⃣ Edit & Build Your Static Webpage**  
- Modify the `index.html`, `style.css`, and `script.js` files to reflect what you learned in the workshop.  
- Use HTML, CSS, and JavaScript to create a visually appealing page!  

#### **5️⃣ Deploy Your Page Using GitHub Pages**  
- Go to your new GitHub repository.  
- Click **Settings** → **Pages**.  
- Under **Branch**, select `main`, then click **Save**.  
- Your site will be live at:  
  ```
  https://YOUR-USERNAME.github.io/my-hackathon-page/
  ```
- Wait a few minutes for GitHub Pages to publish it.  

### **Submission**  
- Share your deployed **GitHub Pages link** with us by submitting it [here](https://docs.google.com/forms/d/e/1FAIpQLSdnbuN0zv3RbaC3RbafCHnkE5QDUoB7QE7znBaGqOjZ7JWFow/viewform?usp=sharing).  
- Collect prizes at our next meeting!     

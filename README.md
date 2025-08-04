# First-Discord-Bot

A simple Discord bot built with Node.js (or Python—adjust as needed). This project is a personal starter template that showcases basic bot functionality using environment variables for configuration.

✨ Features
Connects to Discord via a bot token

Supports basic commands (e.g., hello, assign, remove, dm, reply, poll, secret)

Environment variables managed via .env (token stays local)

Modular code structure (commands/, events/, or Python modules)

Easy to customize and extend

🚀 Getting Started
1. Clone the repo
<pre><code>git clone https://github.com/YashKhawale/First-Discord-Bot.git
cd First-Discord-Bot</code></pre>

2. Install dependencies
For Python:
<pre><code>pip install -r requirements.txt</code></pre>

3. Set up environment variables
Create a .env file (this is not tracked in Git):
<pre><code>DISCORD_TOKEN=your_bot_token_here</code></pre>
Also ensure .env is listed in .gitignore so it doesn’t get pushed.

4. Run the bot
Python (if applicable):
<pre><code>python main.py</code></pre>

🛠️ Usage
Once the bot is running, invite it to your Discord server and use commands like:

Command	Description
!hello	Bot responds with “Hello @mention!”
!dm <msg>	 Bot send you direct message
!reply  Bot replies with "This is a reply to your message!"
!poll <msg>  Bot creates a poll with title <msg> and reaction emojies
!assign  Bot assigns a role to the user
!remove  Bot removes the user's role

(List actual commands implemented in your bot here.)

💡 Configuration & Customization
Add your favorite features by editing or adding modules in relevant folders.

Keep sensitive values like tokens and secrets in .env; never commit them.

Rename or copy .env.example if provided to help others set up their environment.

🧪 Testing & Development Tips
Use a test Discord server for development.

Enable Gateway Intents in the [Discord Developer Portal] for features like message content access if needed.

Use nodemon or Python auto-reload workflows for faster iteration during development.

📝 Notes
This is a lightweight starter—a playground for experimenting.

Be sure to regenerate your Discord token if it ever gets exposed.

Regularly review code best practices and Discord API updates for improvements.

✅ Contribution & Feedback
Feel free to open issues or submit pull requests. Whether you add new commands, refactor, or improve docs—contributions are very welcome!

🧾 License
MIT License
(Update if using another license.)

👤 Contact
Built by Yash Khawale.
Connect with me via GitHub or other platforms.



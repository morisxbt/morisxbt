const githubProfile = {
  username: "morisxbt",
  level: "Beginner",
  isNewbie: true,
  currentActivity: "Learning how to commit and push code",
  message: "Hello everyone! Just created my account. Excited to join the community!",
  systemCheck: function() {
    if (this.isNewbie) {
      console.log(`⚡️ [SYSTEM]: Hello World from ${this.username}!`);
      console.log(`📝 [STATUS]: ${this.message}`);
      console.log("🛠️ [TODO]: Keep learning, coding, and building things.");
    }
  }
};

githubProfile.systemCheck();

const commandInput = document.getElementById("command-input");
const submitButton = document.getElementById("submit-button");
const result = document.getElementById("result");

const commandList = [
  {
    question: "How do you clone a GitHub repo?",
    answer: "git clone <github-repo-url>"
  },
  {
    question: "How do you create a new branch in Git?",
    answer: "git branch <branch-name>"
  },
  {
    question: "How do you merge two branches in Git?",
    answer: "git merge <branch-name>"
  },
  {
    question: "How do you push changes to a Git remote?",
    answer: "git push"
  },
  {
    question: "How do you pull changes from a Git remote?",
    answer: "git pull"
  },
  {
    question: "How do you revert changes in Git?",
    answer: "git revert <commit-hash>"
  },
  {
    question: "How do you see the Git commit history?",
    answer: "git log"
  },
  {
    question: "How do you undo the last commit in Git?",
    answer: "git reset HEAD~1"
  }
];

function handleCommand() {
  const inputText = commandInput.value.toLowerCase();
  const command = commandList.find(
    cmd => cmd.question.toLowerCase() === inputText
  );
  if (command) {
    result.textContent = command.answer;
  } else {
    result.textContent = "Sorry, I didn't understand your question.";
  }
  commandInput.value = "";
}

submitButton.addEventListener("click", handleCommand);
commandInput.addEventListener("keydown", event => {
  if (event.key === "Enter") {
    handleCommand();
  }
});

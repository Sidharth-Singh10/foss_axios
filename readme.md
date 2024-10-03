Here's the contribution guide formatted for direct use in your README file:

```markdown
# Contributing to Assignment Repository

Welcome! This repository is used to manage assignment submissions. To submit your assignment, please follow the steps below.

## How to Submit Your Assignment

1. **Fork the Repository:**
   - Click on the "Fork" button at the top right corner of this repository’s page to create a copy of the repository in your GitHub account.

2. **Clone the Forked Repository:**

   ```bash
   git clone https://github.com/YourUsername/AssignmentRepo.git
   ```

   Replace `YourUsername` with your GitHub username.

3. **Create a New Branch:**

   ```bash
   git checkout -b YourRollNumber
   ```

   Replace `YourRollNumber` with your actual roll number (e.g., `20123456`).

4. **Create a New File:**
   - In the root directory, create a new file named `YourRollNumber.txt`. Replace `YourRollNumber` with your actual roll number.
   - Inside this file, you can add a simple statement like:

     ```
     This is the submission for Roll Number: YourRollNumber
     ```

5. **Commit Your Changes:**

   ```bash
   git add YourRollNumber.txt
   git commit -m "Add assignment submission for Roll Number YourRollNumber"
   ```

   Replace `YourRollNumber` with your actual roll number.

6. **Push Your Branch to Your Forked Repository:**

   ```bash
   git push --set-upstream origin YourRollNumber
   ```

7. **Create a Pull Request:**
   - Go to the original repository.
   - Click on the "New Pull Request" button.
   - Select the branch with your roll number and submit the pull request.

## Additional Notes

- Ensure your file is named exactly as your roll number with `.txt` extension.
- Do not modify any other files in the repository.
- Ensure your pull request is created from a branch named after your roll number.

## Conclusion

Thank you for your submission! We look forward to reviewing your pull request.
```

You can copy and paste this into your README file.
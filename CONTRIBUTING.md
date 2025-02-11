# Contributing to Campus Career Connect

Thank you for considering contributing to **Campus Career Connect**! Your contributions help improve the project and make it more robust and user-friendly. Whether you're fixing bugs, adding new features, improving documentation, or enhancing UI elements, your efforts are appreciated. 🚀

## How to Contribute

### 1. Fork the Repository
- Click the **Fork** button on the top right of this repository.
- This will create a copy of the repository under your GitHub account.

### 2. Clone Your Fork
```bash
git clone https://github.com/eldeshik/Campus_CC.git
cd Campus_CC
```

### 3. Create a Branch
Create a branch for your feature or bug fix:
```bash
git checkout -b feature/your-feature-name
```

### 4. Make Changes
- Implement your feature or fix.
- Ensure your code follows consistent formatting and includes proper comments where necessary.

### 5. Adding Images to the README
If you're contributing screenshots, diagrams, or any other images to improve the documentation:

1. **Save Images:** Place your images in the `images/` directory at the root of the project. If the folder doesn't exist, create one.
   
2. **Naming Convention:** Use clear and descriptive file names that reflect the content of the image. Examples:
   - `dashboard_view.png`
   - `login_page_update.png`
   - `system_architecture_diagram.png`

3. **Referencing Images:** To include the image in the `README.md`, use the following markdown syntax:
   ```markdown
   ![Description of Image](images/your_image_name.png)
   ```
   Example:
   ```markdown
   ![Admin Dashboard View](images/dashboard_view.png)
   ```

4. **Optimizing Images:** Ensure the images are optimized for the web to reduce file size without compromising quality. Use formats like `.png` or `.jpg` and keep file sizes as small as possible.

5. **Commit and Push:** After adding the images and updating the `README.md`, commit your changes and push to your branch:
   ```bash
   git add images/your_image_name.png README.md
   git commit -m "Add: Updated admin dashboard screenshot in README"
   git push origin your-branch-name
   ```

### 6. Commit Your Changes
Make sure your commit messages are descriptive:
```bash
git add .
git commit -m "Add feature: dynamic placement statistics with updated dashboard view"
```

### 7. Push to Your Fork
```bash
git push origin feature/your-feature-name
```

### 8. Create a Pull Request
- Go to the original repository on GitHub.
- Click on **Pull Requests** and then **New Pull Request**.
- Select your branch and submit your pull request, describing the changes you've made.

---

## Code of Conduct

By contributing to this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please be respectful and constructive in your discussions and contributions.

---

## Need Help?

If you're stuck or have questions, feel free to open an issue in the repository. We welcome all feedback, ideas, and suggestions!

Happy Coding! 🎉


echo -e '## Test\n```bash\necho "Hello from PR test"\n```' > README.md
git add README.md
git commit -m "Add test shell command to README"
git push origin feature/pr-runner

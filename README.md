#!/bin/bash

# Create README.md file
echo "# My Project" > README.md
echo "" >> README.md
echo "This is a small project that demonstrates how to use Git to manage code and collaborate with others. The project contains a few basic files, including a \`README.md\` file that provides an overview of the project." >> README.md
echo "" >> README.md
echo "## Installation" >> README.md
echo "" >> README.md
echo "To install the project, simply clone the repository to your local machine using the following command:" >> README.md
echo "" >> README.md
echo "\`\`\`" >> README.md
echo "$ git clone <repository_url>" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "## Usage" >> README.md
echo "" >> README.md
echo "To use the project, navigate to the project directory and run the following command:" >> README.md
echo "" >> README.md
echo "\`\`\`" >> README.md
echo "$ python main.py" >> README.md
echo "\`\`\`" >> README.md
echo "" >> README.md
echo "This will execute the \`main.py\` script and display the output on the terminal." >> README.md
echo "" >> README.md
echo "## Contributing" >> README.md
echo "" >> README.md
echo "If you would like to contribute to the project, please follow these steps:" >> README.md
echo "" >> README.md
echo "1. Fork the repository to your own account." >> README.md
echo "2. Create a new branch for your changes." >> README.md
echo "3. Make your changes and commit them to the new branch." >> README.md
echo "4. Push the branch to your forked repository." >> README.md
echo "5. Open a pull request to the main repository." >> README.md
echo "" >> README.md
echo "We welcome all contributions and appreciate your help in improving the project!" >> README.md

# Add README.md file to Git and commit changes
git add README.md
git commit -m "Added README.md file with project description"

# Push changes to remote repository
git push origin master

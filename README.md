"# npm_random_number_generator" 
# Create a test directory
mkdir random-number-test 
  
# Change into the directory
cd random-number-test 
# Install the package     
npm install faheem-random-number-generator --save
# Create a test file
touch test.js
# Usage
Copy this simple test code and paste it in the test.jsfile.

const randomNumberGenerator = require('faheem-random-number-generator');
console.log(randomNumberGenerator(5, 10));

# For Running

node ./test.js

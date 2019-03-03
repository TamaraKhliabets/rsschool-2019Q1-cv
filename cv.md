# CV
1. Tamara Khliabets
1. Phone number: `+375 29 22 66 949`, email: `tokotomka@gmail.com`
1. The main target is to learn modern technologies for creating web-sites. I'm ready spend a lot of time and going to ideal.
1. Skills
   - JavaScript, ES6, React Redux, Git, MongoDB
1. Code examples
   ```js
   function getZerosCount(number, base) {
       let primeFactors = getPrimeFactors(n = base, base);
       return getMin(countOccurrences(number, primeFactors));
   }
   
   let getPrimeFactors = (n, base) => {
       let arr = [], uniqueArr = [], i = 2;
           while (n > 1 && n <= base) {
              if (n % i === 0) {
                  arr.push(i);
                  n /= i;
              } else if (i === 2) {
                  i++;
              } else {
                  i += 2;
              }
           }
           while (arr.length > 0) {
               uniqueArr.push(arr.filter(e => e === arr[0]));
               arr = arr.filter(e => e !== arr[0]);
           }   
       return uniqueArr;
   };
      
   let countOccurrences = (num, arr) => {
       return arr.map(e => {
           let result = 0, pow = 1;
           while (num / Math.pow(e[0], pow) >= 1) {
               result += Math.floor(num / Math.pow(e[0], pow++));
           }
           return Math.floor(result / e.length);
          });
   };
      
   let getMin = arr => arr.sort((a, b) => a - b)[0];
1. Movie Catalog - [link]()
1. Education
   - Rolling Scopes 2017
   - IT Shark 2018
   - Codeacademy
1. English - 3 years in active use. Speaking / writing level B1. Experience:
   - English courses in 2016
   - Lead in discussion club,  
   - Reading IT Blogs, Programming Education materials, understanding natives video
 
//1.a Print Odd numbers In an array using annonymous
// var result = [];
// var a =function (arr){
//     for(var i=0;i<arr.lenght;i=i+1){
//         if(arr[i]%2!==0){
//             result.push(arr[i]);
//         }
//     }
//     return result;
// }
// console.log(a([15,18,17,19,10,12]));

//1.a Print Odd numbers In an array using IIFE
// var result = [];
// (function (arr){
//   for(var i=0;i<arr.length;i=i+1){
//     if(arr[i]%2!==0){
//         result.push(arr[i]);
//     }
//   }
//   console.log(result) 
// })([1,2,3,4,5,6,7,8])

//2.a Print odd numbers in an array using arrow function
// odd = (arr) => {
//     for(var i=0;i<array.length;i=i+1){
//         if(arr[i]%2!==0){
//             console.log(arr[i])
//         }
//     }
// }


//1.b Convert all the strings to tittle caps in a string array using anonymous
// (function (str) {
//     str = str.toLowerCase().split(' ');
//     for (var i =0;i<str.lenght;i=i+1){
//         str[i] =str[i].chart(0).toUpperCase() + str[i].sllice(1);
//     }
//     return str.join(' ');
// })

//1.b Convert all the strings to tittle caps in a string array using IIFE:
// (function (str) {
//     str = str.toLowerCase().split(' ');
//     for (var i =0;i<str.lenght;i=i+1){
//         str[i] =str[i].chart(0).toUpperCase() + str[i].sllice(1);
//     }
//     return str.join(' ');
// })
// ("INDIA IS MY COUNTRY"); 

//2.b Convert all the strings to tittle caps in a string array using Arrow:
    //   titleCase = (str) => {
    //   str = str.toLowerCase().split(' ');
    //    for (var i =0;i<str.lenght;i=i+1){
    //      str[i] =str[i].chart(0).toUpperCase() + str[i].sllice(1);
    //     }
    //       return str.join(' ');
    //      }

//1.c Sum Of all numbers in an array using anonymus:
//  (function(arr){
//     var sum = 0;
//     for(var i =0;i,arr.lenght;i+1){
//         sum = sum + arrr[i];
//     }
//     return sum;
//  })  

//1.c Sum Of all numbers in an array using IIFE:
//(function(arr){
    //     var sum = 0;
    //     for(var i =0;i,arr.lenght;i+1){
    //         sum = sum + arrr[i];
    //     }
    //     return sum;
    //  })  ([1,2,3,4]) 

//2.C Sum Of all numbers in an array using ARROW:
//sum = (arr)=>{
//var sum = 0;
//     for(var i =0;i,arr.lenght;i+1){
//         sum = sum + arr[i];
//     }
//     return sum;
// }

// 1.d Return all the prime numbers in an array Using anonymous:
//  function(numarr){
//     numArr = numArr.filter((number) => {
//     for (var i=2;i<=Math.sqrt(number);i=i+1){
//         if(num % i ===0)return false;
//     } 
//     return true;   
//     });
//     console.log(numArr);
//  }

//  1.d Return all the prime numbers in an array Using IIFE:

//(function(numarr){
    //     numArr = numArr.filter((number) => {
    //     for (var i=2;i<=Math.sqrt(number);i=i+1){
    //         if(num % i ===0)return false;
    //     } 
    //     return true;   
    //     });
    //     console.log(numArr);
    //  })([1,2,3,4])

  //  2.d Return all the prime numbers in an array Using Arrow:  

  //primeNumber = (numarr) => {
    //     numArr = numArr.filter((number) => {
    //     for (var i=2;i<=Math.sqrt(number);i=i+1){
    //         if(num % i ===0) return false;
    //     } 
    //     return true;   
    //     });
    //     console.log(numArr);
    //  }
//1.e Return all the palindromes in an array Using Anonymous:

// function (arr,n)
// {
//     for (var i=0;i<n;i+1)
// {
//     var ans = isPalindrome(arr[i]);
//     if ( ans == false)
//      return false;
// }
// return true;
// }

//1.e Return all the palindromes in an array Using IIFE:

// (function (arr,n)
// {
//     for (var i=0;i<n;i+1)
// {
//     var ans = isPalindrome(arr[i]);
//     if ( ans == false)
//      return false;
// }
// return true;
// })([1,2,3],3)

//2.e Return all the palindromes in an array Using ARROW:

// Palindrome = (arr,n) =>
// {
//     for (var i=0;i<n;i+1)
// {
//     var ans = isPalindrome(arr[i]);
//     if (ans == false)
//      return false;
// }
// return true;
// }





//1.g  Remove duplicates from an Array Uing anonymous :
// function(array){
//     var dup = [...new Set(arr)];
//     console.log(dup);
// }

// //1.g  Remove duplicates from an Array Uing IIFE :
// (function(array){
//     var duplicate = [...new Set(arr)];
//     console.log(duplicate);
// })([1,2,3,4,5,6])

// 1.h Rotate an array by K Times Uing anonymous:
// function(arr,k){
//     k = k%arguments.length;
//     if(k<0){
//         k+=a.lenght;
//     }
//     reverse(a, 0, a.lenght - k -1);
//     reverse(a, 0, a.lenght - k,a.lenght -1);
//     reverse(a, 0, a.lenght -1);
// }

// 1.h Rotate an array by K Times Uing IIFE:

// (function(arr,k){
//     k = k%arguments.length;
//     if(k<0){
//         k+=a.lenght;
//     }
//     reverse(a, 0, a.lenght - k -1);
//     reverse(a, 0, a.lenght - k,a.lenght -1);
//     reverse(a, 0, a.lenght -1);
// })([1,2,3,4,5,6,7,] , 2)

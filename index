function palindrome(str) {
  const regex = /[\W_]/g
  const string = str.toLowerCase().replace(regex, '')
  const reverseString = string.split('').reverse().join('')

  return string === reverseString
}

console.log(palindrome("A man, a plan, a canal. Panama"));

//Check for Palindromes with a FOR loop.
function palindrome(str) {
  const regex = /[\W_]/g
  str = str.toLowerCase().replace(regex, '')
  for (let i = 0; i < str.length / 2; i++) {
    if (str[i] !== str[str.length - 1 - i])
    return false
  }
  return true
}

palindrome("A man, a plan, a canal. Panama")

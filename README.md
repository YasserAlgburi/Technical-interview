# Technical-interview



📝 TODO: Complete this section
Your name and PID:Yasses Algburi yasseralgburi

Your partner's name and PID:Yoonje lee, ylee201

Link to selected coding challenge: https://leetcode.com/problems/merge-strings-alternately/description/?envType=study-plan-v2&envId=leetcode-75
/**
 * @param {string} word1
 * @param {string} word2
 * @return {string}
 */
var mergeAlternately = function(word1, word2) {
  let result = '';

  for (let i = 0; i < Math.max(word1.length, word2.length); i++) {

    if (i < word1.length) result += word1[i];

    if (i < word2.length) result += word2[i];
  }
  return result;
};

Summary of partner's interview feedback: the cadidate was exellent in solving and understanding the problem and edge cases. Worked thougoutly explaining the code to the interviewer of his thought procress.

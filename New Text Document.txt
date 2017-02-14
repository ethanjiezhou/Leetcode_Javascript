/**
 * @param {string} s
 * @return {string}
 */
// var reverseString = function(s) {
//     return s.split('').reverse().join('');
// };

var reverseString = function(s) {
    var result = '';
    var length = s.length;
    for(var i = 0; i < length; i++){
        result += s.charAt(length - 1 - i);
    }
    return result;
};
# Alexander Ivanov

---

## Contacts

- **Location:** [Russia, Kurgan](https://www.google.com/maps/@55.4559652,65.3045688,12.01z)
- **Github:** [@Dudarik](https://github.com/Dudarik)
- **Email:** [dudarik@yandex.ru](mailto:dudarik@yandex.ru)
- **Telegram:** [@AlWh45](https://t.me/AlWh45)
- **Discord:** [@AlWh](https://discord.com/channels/AlWh#6445)

## About me

<!--TODO About me. This is so hard for me-->

## Skills

- HTML5, CSS3
- JavaScript (fundamentals, ES6, OOP, asynchronous)
- React JS (basic, react context, with hooks)
- React router V6 (basic)
- Redux/toolkit (basic)
- Node JS (basic)
- REST API (basic)
- SQL DB/NoSQL DB (basic)
- Git/Github
- OS: Windows, MacOS, Linux(Ubuntu)
- IDE: VSCode

## Code example:

##### [Leetcode.com](https://leetcode.com/problems/sort-array-by-parity/)

##### 905. Sort Array By Parity

    Given an integer array nums, move all the even integers at the beginning of the array followed by all the odd integers.
    Return any array that satisfies this condition.

```javascript
/**
 * @param {number[]} nums
 * @return {number[]}
 */

var sortArrayByParity = function (nums) {
  return nums.sort((a) => (a % 2 ? 1 : -1));
};
```

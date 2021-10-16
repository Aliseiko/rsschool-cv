# Ivan Aliseiko

## Contacts

* **Location:** Minsk, Belarus
* **Phone:** +375 (29) 1-199-198
* **Email:** aliseiko.dev@gmail.com
* **GitHub:** [Aliseiko](https://github.com/Aliseiko)

## Skills

* **HTML**
* **CSS**
* **JavaScript** (in progress)

## Code example

**Codewars Kata:** Reverse every other word in the string.\
*Reverse every other word in a given string, then return the string. Throw away any leading or trailing whitespace,
while ensuring there is exactly one space between each word. Punctuation marks should be treated as if they are a part
of the word in this kata.*

```
function reverse(str) {
    return str.split(' ').reduce((acc, item, index) => {
        if (index % 2 === 0) {
            acc += ' ' + item;
        } else {
            acc += ' ' + item.split('').reverse().join('');
        }
        return acc.trim();
    }, '');
}
```

## Education



## Experience



## Languages

* **Russian** - native speaker
* **English** - B1 (intermediate) according to [EFSET](https://www.efset.org/quick-check/)
## **KISLY NIKITA**

### **Engineer**

---

### **My contacts**

---

|  **Adress:**  |       The Republic of Belarus, Minsk city |
| :-----------: | ----------------------------------------: |
|  **Phone:**   |                       +375 33 312 35 \*\* |
|  **E-mail:**  |                       <sour945@gmail.com> |
|  **Github:**  | [pa4ka1992](https://github.com/pa4ka1992) |
| **Telegram:** |       [pa4ka1992](https://t.me/pa4ka1992) |
| **Discord:**  |                 Nikita Kisly (@pa4ka1992) |

### **About me**

---

I'm 30, and i have been working as a civil engineer in the Belarusian company, like for 6 years. I graduated Yanka Kupala State University of Grodno with an emphasis in building production in 2014. Since 2017 i've started to learn a basic programming skills and conceptions, because i was always enjoyed in creating something brand-new and researching an Internet related technologies. A little bit later, i realized that JavaScript is the number one language to work with in Internet, so i picked it like a main to study.

### **Skills**

---

- HTML5
- CSS3
- JavaScript
- Git/GitHub
- Figma
- VBA
- databases (basic knowledge)
- professional google user

### **Code Example**

---

[Kata](https://www.codewars.com/kata/5b6db1acb118141f6b000060/javascript) solution

```javascript
function recycle(array) {
    const recycles = [
        { recType: "paper", recycle: [] },
        { recType: "glass",recycle: [] },
        { recType: "organic", recycle: [] },
        { recType: "plastic", recycle: [] }
    ]
    array.forEach(({ type, material, secondMaterial }) => {
        recycles.map(({ recType, recycle }) => {
            if (recType == material) {
                recycle.push(type)
            }
            if (secondMaterial && secondMaterial == recType) {
                recycle.push(type)
            }
        })
    })
    return recycles.map((extract) => {
        return extract.recycle
    })
}
```
## Mezhueva Evgenia

### Front-End Developer

---

### **Conact information:**

**Location:** Georgia, Batumi

**Phone:** +995 591 701 612

**Email:** sometestemail@gmail.com

**[LinkedIn](https://www.linkedin.com/in/evgeniya-mezhueva/)**

---

**About me:**

Junior Front-End developer with good programming skills and strong desire to grow.
I have proper understanding of HTML5, CSS3, responsive web design and JavaScript. I'm a self-organized, hard-working, detail-oriented person with strong communication and interpersonal skills.

---

### **Skills:**

- HTML
- CSS
- JavaScript
- Git
- React
- Material UI
- Jira
- Linux

---

### **Code Example:**

The **getYears** function calculates the maximum loan term (an integer number of years) based on the loan amount (**amount**), annual interest rate (**percent**), and client limit (**limit**).

```
function getYears(amount, percent, expectedLimit) {
  let years = 0;

  while (amount + amount * percent / 100 <= expectedLimit) {
    amount = amount + amount * percent / 100;
    years++;
  }

  return years;
}
```

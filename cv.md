# Olga Rymkevich

### Contact information:

**Phone:** +375 29 603-86-32
**E-mail:** lilu.rymkevich@mail.ru
**GitHub** @LiluViolet
**Discord** Olga Rymkevich#1292

---

### About Myself:

Hi, I'm Olga and I'm 29 years old. I graduated from Vitebsk State Medical University in 2015 with a degree in pediatrics. But after working as a doctor for several years, I was disappointed to see from the inside how patients treat you. I decided that it was time to change something and try a different life! And I chose programming, since from school times I easily and with interest found a common language with a computer. And now, being at the initial stage of studying a new profession, I see how this process captivates me and enthusiastically "absorb" the information and move on. I am responsible and can work in a team, I have organizational skills (I headed the pediatric department for two years), and always strive to learn something new and strengthen my knowledge.

---
### Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- VS Code
- Adobe Photoshop

---

### Code example:
```javascript
function revrot(str, sz) {
	if (!sz || sz < 0 || sz > str.length)
		return '';
var arr = str.match(new RegExp('\\d{'+sz+'}','g'));
return arr.map(function(v) {
	if (v.toString().split('').reduce((s,v) =>
		s + v * 1,0) % 2 === 0) {
return v.split('').reverse().join('');
}
else return v.slice(1) + v[0];
}).join('');
}
```
---

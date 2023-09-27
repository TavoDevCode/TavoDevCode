# Hi there

**This workspace is designed to help me organize my daily activities using Notion. 💗**

---

![https://i.pinimg.com/originals/39/82/8c/39828c7dab661d0a305b43744dd9745e.gif](https://i.pinimg.com/originals/39/82/8c/39828c7dab661d0a305b43744dd9745e.gif)

```tsx
class Message {
	private message: string
  
	constructor() {
		this.message = "Hi my name is Gustavo Hernandez Hidalgo 🍰!"
	}

  showInConsole() {
    console.log(this.message);
  }

  showInAlert() {
    alert(this.message);
  }

  showContentInHTML(elementId: string) {
    const element = document.getElementById(elementId);
    
		if(element === undefined) return console.error(`Element Id '${idElemento}' error 💔!`);

		element.innerHTML = this.message;
  }
}
```

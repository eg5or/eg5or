```javascript
if (idea > 0 && decentPay === true) {
  const phoneNumber = '8-926-340-01-..'
  telegram === true ? telegram.sendMessage('@eg5or') : whatsapp.sendMessage(phoneNumber)
} else {
  console.log('See you later')
}

const mySkills = ['javaScript', 'React', 'Redux', 'nodeJS', 'express']

const yourProject = (mySkills, idea, decentPay) => {
  const work = mySkills.map(skill => skill * idea)
  let profit = work / decentPay 
  return profit
}

yourProject(mySkills, idea, decentPay)
```

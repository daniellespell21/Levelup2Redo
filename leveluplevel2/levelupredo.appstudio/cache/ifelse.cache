let userName = prompt("Please enter your name.")
userName1=userName.charAt(0).toUpperCase() + userName.substring(1);
let state = prompt("Please enter the two-letter abbreviation of your state.")
state1= state.toUpperCase()
let temp = prompt("Please enter the temperature.")
let message = ["	wear a warm coat, hat, scarf and gloves.", "wear a warm coat but you won't need a hat, scarf or gloves.", "wear your warmest coat, a warm hat, a scarf, and warm gloves.", "	wear a warm coat, hat and gloves. Maybe a scarf too."]

if (state1 == "NE" && temp < 32) {
  NSB.MsgBox(`Hello ${userName1}, ${message[0]}`)
} else if (state1 == "NE" && temp >=32 && temp <=50) {
  NSB.MsgBox(`Hello ${userName1}, ${message[1]}`)
}  else if (state1 == "FL" && temp >=32 && temp <=50) {
  NSB.MsgBox(`Hello ${userName1}, ${message[2]}`)
}  else if (state1 == "FL" && temp >50 && temp <=70) {
  NSB.MsgBox(`Hello ${userName1}, ${message[3]}`)
}  else {
  NSB.MsgBox(`Hello ${userName1}, please enter valid information.`)
}
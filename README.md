function diana(input) {
let jsSkillFrom1To10 = Number(input[0])
let motivationScale = Number(input[1])
let currentMindset = input[2]

let totalChanceForADiploma = jsSkillFrom1To10 + motivationScale

if (currentMindset == "always learning" && totalChanceForADiploma >= 15) {
console.log(`Your chances are ${totalChanceForADiploma}`)
} else {
console.log('Please try again later.')
}
}
diana([10, 10, "always learning"])




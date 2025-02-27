```swift
// Hello there!
struct Person {
  let name: String = "Dario Crippa"
  let nickname: String = "AstroWLAN"
  let nationality: String = "🇮🇹"
  let languages: [String] = ["Italian", "English", "Swift", "C", "Python", "JavaScript", "Java"]
  let education: College = MSc. CompSci and Engineering @ Politecnico di Milano

  func contactMe(message : String) {
    let email = dario.crippa97@gmail.com
    email.send(message)
  }

  func jobOffer() {
    linkedin.connect("https://www.linkedin.com/in/dario-crippa-223ba9267/")
  }
}
```

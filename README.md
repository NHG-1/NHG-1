package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "Sabbir Hossain"
  me.username = "NHG-1"
  me.age      = "18"
  me.job      = "AI developer | Web developer"
  me.hobbies  = []string{"code", "anime", "music"," guiterist"," gaming"}
  
  fmt.Println(me)
}

package main

import "fmt"

var n int

func main() {
	for i := 0; i <= 100; i++ {
		if i%3 == 0 && i%5 == 0 {
			fmt.Println("Ping ", "Pang")
		} else if i%3 == 0 {
			fmt.Println("Ping")
		} else if i%5 == 0 {
			fmt.Println("Pang")
		} else {

			fmt.Println(i)
		}
	}
}

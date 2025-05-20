+++
title = "Pizzeria App: A Delicious Web App Journey with Go"
outputs = ["Reveal"]
[logo]
src = "./img/stuttgart_gophers.png"
[reveal_hugo]
margin = 0.2
+++

{{< slide background-color="#008080" >}}

<div class="title-slide">
<h1>Pizzeria App</h1>
<h2>A Delicious Web App Journey with Go</h2>
<p>Presented by: AlexTLDR</p>
</div>

---

# Why Go?

<div class="responsive-container">
  <ul class="responsive-list">
    <li class="fragment">The syntax is minimalistic and clean, inspired by C but much more readable.
      <div class="fragment">
        {{< highlight go >}}
package main

import "fmt"

func main() {
message := "Hello, pizza lovers!"
fmt.Println(message)
}
{{< /highlight >}}

</div>
</li>
<li class="fragment">Consistently formatted with gofmt - no style debates.</li>
<li class="fragment">Fast compilation and execution times.</li>
<li class="fragment">Rich Standard Library (our example with the website, HTTP servers, file I/O, JSON handling, etc) - you can build full applications without relying heavily on external dependencies</li>

  </ul>
</div>

---

# Why Go?

<div class="responsive-container">
  <ul class="responsive-list">
    <li class="fragment">Backwards compatible.</li>
    <li class="fragment">Static typing (preference-based - I love this feature as it makes the code base less confusing).</li>
    <li class="fragment">Cross-Platform & Deployment-Friendly (run your program as a binary).</li>
    <li class="fragment">DevOps oriented:
      <ul>
        <li class="fragment">Great for containerized apps and microservices</li>
        <li class="fragment">Widely used in cloud-native environments (Docker, Kubernetes, Terraform, ETC.)</li>
        <li class="fragment">Great fit for CLI tools and backend infrastructure</li>
      </ul>
    </li>

  </ul>
</div>

---

# Learning resources

<div class="responsive-container">
  <ul class="responsive-list">
    <li class="fragment">A Tour of Go / Ultimate Go Tour</li>
    <li class="fragment">Go Bootcamp Master Golang with 1000+ Exercises and Projects (last updated in 2021 but still relevant)</li>
    <li class="fragment">Boot.dev</li>
    <li class="fragment">Ardan Labs - in-depth training</li>
  </ul>
</div>

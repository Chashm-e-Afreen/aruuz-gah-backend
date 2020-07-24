<p align="center">
  <a href="" rel="noopener">
 <img width=276.5px height=552px src="https://raw.githubusercontent.com/Chashm-e-Afreen/aruuz-gah-frontend/master/img/YinTrue-min.png?token=AM2FQFZKLSVFUREJQQFJEW27EQEM2" alt="Project logo"></a>
</p>

<h3 align="center">Aruuz Gah</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
        An online prosodist for Urdu poetry.
        <br>
        <a href= "aruuz.rocks/">Aruuz Rocks!</a>
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
Aruuz Gah is a web application with a modern UI design that can analyse the meter of Urdu couplets, pinpoint errors and suggest fixes for lines that do not conform to a standard meter. Aruuz refers to the system of scansion for Urdu and Persian poetry. The algorithm has been scrupulously crafted keeping the needs and oft-repeated mistakes of beginners in mind.

## 🏁 Getting Started <a name = "getting_started"></a>
 See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites
You just need the latest [Go distribution](https://golang.org/doc/install) to get this project up and running. All dependencies have been put into the vendor folder. Just clone the project into your %GOPATH/src/ directory and it should be ready to go. You can get the Go on arch(the environment I happen to use) with the following command.

```
Sudo Pacman -S go
```

### Installing
Once the project is in the right directory, you just have to build it.

Let's say we want to generate a binary named aruuz.

```
go build -o aruuz
```

And then to run the binary

```
./aruuz
```
The server will start listening at port 3000.

## 🎈 Usage <a name="usage"></a>
If you want to locally run the system I'll suggest downloading the [frontend](https://github.com/Chashm-e-Afreen/aruuz-gah-frontend) too. Then you could just run the go binary and head over to the frontend localhost and use the programme like you do online. Using the programme only requires you to enter text in the given textbox and it would generate the appropriate ouptut once you click the button underneath the textarea.

## 🚀 Deployment <a name = "deployment"></a>
Deploying the project is as easy as building it. You just have to clone the project to $GOPATH/src and run the binary.

## ⛏️ Built With <a name = "built_using"></a>
- [Go](https://golang.org/) - Language
- [Fiber](https://gofiber.io/) - Web Framework

## ✍️ Authors <a name = "authors"></a>
- [@Muhammad Rehan Qureshi](https://github.com/Chashm-e-Afreen/) 
- Find my writings at [my blog](chashm-e-afreen.github.io/)

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- Folks at UrduWeb for inspiration and encouragememnt

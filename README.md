# Go Fyne Application

This repository contains a simple Go application built using the Fyne.io toolkit. It demonstrates the basic usage of Fyne to create a graphical user interface (GUI) application.

## Prerequisites

Before running this application, please make sure you have the following installed:

- Go (version 1.16 or higher)
- Fyne.io (version 2.0 or higher)

## Installation

To install Go, please follow the official installation guide for your operating system, which can be found at: https://golang.org/doc/install

To install Fyne.io, you can use the following commands:

```powershell
go get fyne.io/fyne/v2
```

Fyne.io requires C compiler. Recommend mingw installed via scoop:

```powershell
irm get.scoop.sh | iex
scoop install mingw
```

See https://developer.fyne.io/started/

## Running the Application

To run the application, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the directory containing the `main.go` file.
3. Run the following command:

```powershell
go run main.go
```

This will compile and run the application.

## Usage

Upon running the application, you will see a window titled "Dikdik" with a menu bar at the top. The menu bar consists of a "File" menu and a "Help" menu.

- The "File" menu has a single option, "Quit," which allows you to exit the application.
- The "Help" menu has an "About" option that displays information about the application.

In the main window, you will find the following components:

- A welcome text centered in the window.
- An image of a Dik-dik (an antelope species).
- A "Random" button.

Clicking the "Random" button will fetch a random Dik-dik image from the KuteGoAPIURL and update the displayed image accordingly.

You can close the application by clicking the "Quit" option in the "File" menu or by pressing the Escape key.

## Credits

This application was orignially created by [Aurélie Vache](https://dev.to/aurelievache/learning-go-by-examples-part-7-create-a-cross-platform-gui-desktop-app-in-go-44j1)

## License

This project is licensed under the [MIT License](LICENSE).
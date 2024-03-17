# colorable

This is a fork of the project github.com/mattn/go-colorable by Yasuhiro Matsumoto (a.k.a mattn). 

The fork was made to get rid of addiction and increase the reliability of my applications. Links to the author and the original repository have been saved. 

Colorable writer for windows. 

## Usage

```go
logrus.SetFormatter(&logrus.TextFormatter{ForceColors: true})
logrus.SetOutput(colorable.NewColorableStdout())

logrus.Info("succeeded")
logrus.Warn("not correct")
logrus.Error("something error")
logrus.Fatal("panic")
```

You can compile above code on non-windows OSs. 

## Installation

```
$ go get github.com/Kwynto/colorable
```

# License

MIT

# Author

Yasuhiro Matsumoto (a.k.a mattn)

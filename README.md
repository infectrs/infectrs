<h1>Information</h1>

```golang
type Information struct {
	Username  string
	Age       int
	Knowledge []string
	Tools     []string
	Projects  []string
	Contact   map[string]string
}

func NewUser() Information {
	return Information{
		Username:  "Infect",
		Age:       16,
		Knowledge: []string{"JS", "Golang"},
		Tools:     []string{"Visual Studio Code"},
		Projects:  []string{"CapSolver API Wrapper", "WindMouse Go Implementation", "Geetest Captcha Solver", "Binance Captcha Solver"},
		Contact: map[string]string{
			"Discord":  "infectrs",
			"Telegram": "infectre",
		},
	}
}
```

<h2>Stats</h2>

[![infectrs's GitHub stats](https://github-readme-stats.vercel.app/api?username=infectrs)](https://github.com/anuraghazra/github-readme-stats)

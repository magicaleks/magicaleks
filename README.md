[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=00ADD8&center=true&vCenter=true&width=650&lines=Hey%2C+I'm+Aleks+Zenitsin+%F0%9F%91%8B;Backend+Engineer;Python+%2F+Go+%2F+Java+%2F+Elixir)](https://git.io/typing-svg)

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/magicaleks)
![Profile Views](https://komarev.com/ghpvc/?username=magicaleks&color=00ADD8&style=for-the-badge)

```python

class BackendEngineer:

    def __init__(self):
        self.name = "Aleks Zenitsin"
        self.role = "Backend engineer"
        self.language_spoken = ["ru_RU", "en_US"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = BackendEngineer()
me.say_hi()
```

```solidity

contract BlockchainDeveloper {

    string constant myDevTag = "@magicaleks";
    string constant deFiProject = "Ruble stablecoin";
    bool constant isOpenForFunding = true;

    function contactWithMe() external payable returns (string memory) {
        return "Check my profile and contact me with your favourite messenger!";
    }
}
```

```go

package main

import (
	"fmt"
	"sync"
)

func deploy(service string, wg *sync.WaitGroup) {
	defer wg.Done()
	fmt.Printf("🟢 service/%s is up\n", service)
}

func main() {
	services := []string{"api-gateway", "auth", "payments", "notifications"}
	var wg sync.WaitGroup

	for _, svc := range services {
		wg.Add(1)
		go deploy(svc, &wg)
	}

	wg.Wait()
	fmt.Println("🚀 All systems operational")
}
```

```java

import java.util.List;

void main() {
    record Skill(String name, int years) {}

    var stack = List.of(
        new Skill("Python", 4),
        new Skill("Go",     2),
        new Skill("Java",   3),
        new Skill("Elixir", 1)
    );

    stack.stream()
        .filter(s -> s.years() >= 2)
        .sorted((a, b) -> b.years() - a.years())
        .map(s -> "⭐ %-8s %dy".formatted(s.name(), s.years()))
        .forEach(System.out::println);
}
```

```elixir

defmodule Pipeline do
  def deploy([]),            do: IO.puts("✅ All services live")
  def deploy([svc | rest]) do
    IO.puts("🔄 Deploying #{svc}...")
    deploy(rest)
  end
end

Pipeline.deploy(~w[api-gateway auth-service payments-api notification-worker])
```

## 🔧 Technologies & Tools

![Tech Stack](https://skillicons.dev/icons?i=python,go,java,elixir,fastapi,mongodb,postgresql,docker&theme=dark)

## 📊 GitHub Stats

| | |
|---|---|
| ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=magicaleks&show_icons=true&theme=tokyonight&hide_border=true&height=165) | ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=magicaleks&layout=compact&theme=tokyonight&hide_border=true&height=165) |

![Streak](https://streak-stats.demolab.com?user=magicaleks&theme=tokyonight&hide_border=true)

## 🏆 Trophies

![Trophies](https://github-profile-trophy.vercel.app/?username=magicaleks&theme=onedark&no-frame=true&row=1&column=7)

## 🗂️ Highlight Projects

> Add your pinned repositories here using the template below:
>
> ```
> [![Repo](https://github-readme-stats.vercel.app/api/pin/?username=magicaleks&repo=REPO_NAME&theme=tokyonight)](https://github.com/magicaleks/REPO_NAME)
> ```

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/magicaleks/magicaleks/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/magicaleks/magicaleks/output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/magicaleks/magicaleks/output/github-contribution-grid-snake.svg">
</picture>

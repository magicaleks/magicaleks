<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=2,3,12,19,24&amp;height=180&amp;section=header&amp;text=Aleks%20Zenitsin&amp;fontSize=52&amp;fontColor=ffffff&amp;fontAlign=50&amp;fontAlignY=36&amp;desc=AI%20and%20Backend%20Engineer&amp;descFontSize=20&amp;descFontColor=ffffff&amp;descAlign=50&amp;descAlignY=56&amp;animation=fadeIn" alt="Header" width="100%">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/magicaleks)
![Profile Views](https://komarev.com/ghpvc/?username=magicaleks&color=00ADD8&style=for-the-badge)

### 🐍 Python — my native language. Production runs on it, and so do I.

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

### ⛓️ Solidity — wrote a DeFi protocol, survived.

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

### 🐹 Go — goroutines at 3am. Zero regrets.

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

### ☕ Java — enough to be dangerous. Mostly to myself.

```java

import java.util.List;

void main() {
    record Skill(String name, int years) {}

    var stack = List.of(
        new Skill("Python", 4),
        new Skill("Go",     2),
        new Skill("Java",   3)
    );

    stack.stream()
        .filter(s -> s.years() >= 2)
        .sorted((a, b) -> b.years() - a.years())
        .map(s -> "⭐ %-8s %dy".formatted(s.name(), s.years()))
        .forEach(System.out::println);
}
```

## 🔧 Technologies & Tools

![Tech Stack](https://skillicons.dev/icons?i=python,go,java,fastapi,mongodb,postgresql,docker&theme=dark)

## 📊 GitHub Stats

![Stats](./profile/stats.svg)

![Top Languages](./profile/top-langs.svg)

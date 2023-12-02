```
.　　　　　　　　　　 ✦ 　　　　   　 　　　˚　　　　　　　　　　　　　　*　　　　　　　　　　　　.　　　ﾟ
　　　　　　　　　　.　　　　　　　　　　　　　　. 　　 　　　　　　　 ✦ 　　　　　　　　 　            
          　　　　 　　　　　　　　　　　　,　　                             ☀️               .
.　　　　　　　　　　　　　.　　　ﾟ　  　　　.　　　　　　　　　　　　　.　　　　　　　　　　.　　  ✦
　　　　　　,　　　　　　　.　　　　　　    　　　　 　　　　　　　　　　　　　　　　  　　　　
　　　　　　　　　　　　　　    　      　　　　　        　　　　　　　　　　　. 　　　　　　　　　　.
　　　　　　　　　　　. 　　　　　　　　　　　　.　　　　       　   　　 
　　       　   　　　　　　　　　　　　　　　˚　       　    ✦ 　 　　　,　　　　 　　,
　　　 　 　　　　　　　　　　　　.　　　　　 　　 　　　.　　　　　　　　　　　 　   🌑
    　　　　　　　　　　　　　　　˚　　　 　   　　　　,　　　　　　　　　       
　　　　　　.　　　  　　    　　　　　 　　　　　.　　　　　　　　　　　.　   🚀  
　　　　* 　　   　　　　　 ✦ 　　　　　　　         　       　　　 　　 　　　　　　　 　　　　　.
　　　　　　　　　　　　　.　　　　　    　　. 　 　　　　　.　　  　　　　　   　　　　　.　　
　　　　　　　　　.　　　　　　　　　　   　                                                    .
　˚　　　　　　　　　　　　　　　　　　　　　ﾟ　　　　　.　　　　　 🌎　  
,　 　　　　　　　　　　　　　　* .　　　　　 　　　　　　　　　　　　.　　　　　　　　　
 　 ✦ 　　　　   　 　　　˚　　　　　　　　　　　　　　*　　　　   　　　　　　　　　, 　　　　 ✦
　.　　　　　　　　　　　　　　.  　　* 　　   　　　　　 ✦             .              .

```

```py
from dataclasses import dataclass, field

@dataclass
class Me:
    name: str
    website: str
    organization: str
    languages: list[str] = field(default_factory=list)
    gh_user_id: int = field(init=False, default=65181690)


def main() -> None:
    myself = Me(
        name="QAEZZ", website="https://qaezz.dev",
        organization="https://thcotd.org",
        languages=["python", "c sharp", "javascript"])
    print(myself)

if __name__ == "__main__":
    main()


# Me(
#     name='QAEZZ',
#     website='https://qaezz.dev',
#     organization='https://thcotd.org',
#     languages=[
#         'python',
#         'c sharp',
#         'javascript'],
#     gh_user_id=65181690
# )
```

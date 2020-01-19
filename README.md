# scrapbox 🧰
some maybe useful code snippets 


## random major note
```
List<int> majorSemiTone = new List<int> {
  0, 2, 4, 5, 7, 9, 11, 12
};

int rand = majorSemiTone.PickRandom();
float pitch;
if (rand == 0){
    pitch = 1f;
} else {
  pitch = Mathf.Pow(1.05946f, rand);
}
```

## next index (but with looping)

```
(currentIndex + 1) % (listLength);
 ```

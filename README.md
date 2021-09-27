# Python Projects: Create A Dictionary 🐍
This repo contains python code that create a dictionary.<br>
Run the code.


Python
```python
def dictionary(words, pos, meanings):
    for word, pos, meaning in zip(words, pos, meanings):
        print(f'{word} : {pos} : {meaning}')

words = ['ability', 'abroad', 'actor']
# pos stands for part of speech
pos = ['noun', 'adverb', 'noun']
meanings = ['ability to do something the fact that somebody/something is able to do something', ' in or to a foreign country', 'a person who performs on the stage, on television or in films, especially as a profession']

dictionary(words, pos, meanings)

```

Output
```python
ability : noun : ability to do something the fact that somebody/something is able to do something
abroad : adverb :  in or to a foreign country
actor : noun : a person who performs on the stage, on television or in films, especially as a profession

```


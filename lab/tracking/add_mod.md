# Question
In a git repository, file `algo.txt` is tracked and unmodified.
Then we do
```
echo "dijkstra" >> algo.txt
git add algo.txt
```

What will happen?
- [x] Git creates a new blob 
- [ ] Git updates the index file
- [ ] Git updates the current working tree

# Explanation
A new blob is created to store information but wont be added to the index file until it is commited

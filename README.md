# markdown-mermaid
Testing flowchart by using mermaid

## example graph
```mermaid
  graph LR;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

## example flowchart
```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
​```
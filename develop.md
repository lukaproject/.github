# develop

If you want to develop this project, you can clone all repos atur, protos, schedulersvr, schrun in the same dir. like this 
```bash
dxyinme@dxyinme-PC:~/lukaproject$ ls
atur  protos  resource  schedulersvr  schrun
```
and you can run 
```bash
go work init
go work use schedulersvr
go work use schrun
go work use protos
```
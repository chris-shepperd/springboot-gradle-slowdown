# springboot-gradle-slowdown


**with maven exclusions, no classifier**
```
> gradle clean build 
Total time: 10.197 secs
```
**with maven exclusions, with classifier**
```
> gradle clean build 
Total time: 9.819 secs
```
**ignoring maven exclusions, no classifier**
```
> gradle clean build 
Total time: 1.303 secs
```
**ignoring maven exclusions, with classifier**
```
> gradle clean build 
Total time: 1.344 secs
```
**with maven exclusions, no classifier**
```
> gradle engines:avprm-bom:clean engines:avprm-bom:build 
Total time: 5.962 secs
```
**with maven exclusions, with classifier**
```
> gradle engines:avprm-bom:clean engines:avprm-bom:build 
Total time: 9.334 secs
```
**ignoring maven exclusions, no classifier**
```
> gradle engines:avprm-bom:clean engines:avprm-bom:build 
Total time: 0.844 secs
```
**ignoring maven exclusions, with classifier**
```
> gradle engines:avprm-bom:clean engines:avprm-bom:build 
Total time: 0.92 secs
```


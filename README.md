# cicddemo

```
language: java

jdk:
    - openjdk7
    - oraclejdk7

after_success:
   - mvn clean cobertura:cobertura
   - mvn test

notifications:
   email:
       recipients:
          - mymail@gmail.com
```

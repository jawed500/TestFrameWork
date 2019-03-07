---
## CI and CD pipeline
### API based application testing
---
### Where do we start? 
---
### Setup goals:
1. Dedicated SDET in CI place
2. All product teams on board with CI processes
3. Team ownership not individuals 
4. Repeatable and disposable framework
5. Quality in every stage of the pipeline
---
#### Test Scenario: reliability
![CI Component Test](template/img/CI_Components_Testing.png)
1. A system with 100 components each having 99% reliability, would yield 37% reliable
2. Would you release it?  
---
### How do we ensure 100% reliability? 
---
1. 100% SLA (or close), ensure reliability at the lowest level
2. If cannot ensure and measure reliability at lowest level, cannot possible do that at system level 
3. Unit Testing?
---
![CI Framework](template/img/CI_Framework.png)
---
How to develop test process? 
---
![CI Test Process](template/img/CI_TestProcess.png)
---
### Test candidate automation? 
1. Test must effectively exercise the use of the components and test must be run often
2. Return on Investment 
3. Complex business logic
4. Large data
5. Different sets of users
6. Data-Driven
---
### Enhancements? 
1. Tests are part of architectural components
2. Test Categorisation and structure specially codebase increases
3. More tests if always run takes longer to complete 
4. hurdle instead of key to success
---
![CI Framework Categorise](template/img/CI_Framework_Categorise.png)
---
##### Selecting tools, given API based application: 
1. Postman 
2. Rest-Assured 
3. Golang
4. Gatling
---
# ?

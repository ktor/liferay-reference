# liferay-reference
The project serves as an index of Liferay CE 7 code. It's meant to include all Liferay 7 code as dependency.
 
## Usage
It's meant to be opened with an IDE that supports maven an can index all dependencies together with sources like Intellij IDEA for example.
 
Once imported user can leverage all IDE tools like Intellij IDEA [structural search][1], [go to implementation][2], full text search etc. to find API's and sources he's interested in.
  
### Basic facts
* The project uses release.portal.bom artifact from Liferay as a base. 
* The project is not meant to be built. 
* The project contains no own sources.

### Another solution
The project creates IntelliJ IDEA project modules that contains whole Liferay 7 code: https://github.com/holatuwol/liferay-intellij

## License
LGPL-2.1

[1]: https://www.jetbrains.com/help/idea/structural-search-and-replace.html
[2]: https://www.jetbrains.com/help/idea/navigating-through-the-source-code.html#go_to_implementation

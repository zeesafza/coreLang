# coreLang
coreLang is a probabilistic modeling and simulation language for the abstract domain of IT. More specifically, it is a domain specific language (DSL) created with [MAL (the Meta Attack Language)](https://mal-lang.org/).

## About this branch

This "stable" version of the language is the one that was presented on the paper titled "An Attack Simulation Language for the IT Domain" (http://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A1529801&dswid=-8622). If you want to experience the full power of coreLang check out the "master" branch of this repository!

## Project's file structure

This project has the following structure:

* The file `pom.xml` is the Maven configuration file of the project.
* The language itself, the MAL specification, is found on the `*.mal` files located on the [src/main/mal](src/main/mal) directory.

Since this is a Maven project it is ought to be opened by any compatible IDE or to be used with the mvn command line tool.

## Previous work

| Project | Link |
| --- | --- |
| Old coreLang | <https://github.com/pontusj101/coreLang> |
| Core MAL specification of awsLang | <https://gist.github.com/maxwalls/ace99182d064087d2023553337e953c4> |

## License

Copyright © 2019-2020 [coreLang contributors](https://mal-lang.org/coreLang/contributors.html)

All files distributed in the coreLang project are licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), except for the following files:

| File | License |
| --- | --- |
| [`Application.svg`](src/main/resources/icons/Application.svg) | <img src="src/main/resources/icons/Application.svg" alt="Application.svg" width="32" height="32"/> "[code](https://thenounproject.com/term/code/409495/)" icon by [iconsphere](https://thenounproject.com/iconsphere/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Connection.svg`](src/main/resources/icons/Connection.svg) | <img src="src/main/resources/icons/Connection.svg" alt="Connection.svg" width="32" height="32"/> "[connection](https://thenounproject.com/term/connection/2968722/)" icon by [faisalovers](https://thenounproject.com/muhammadfaisal40/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Credentials.svg`](src/main/resources/icons/Credentials.svg) | <img src="src/main/resources/icons/Credentials.svg" alt="Credentials.svg" width="32" height="32"/> "[Key](https://thenounproject.com/term/key/2284382/)" icon by [Eagle Eye](https://thenounproject.com/eagleeye/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Data.svg`](src/main/resources/icons/Data.svg) | <img src="src/main/resources/icons/Data.svg" alt="Data.svg" width="32" height="32"/> "[Data](https://thenounproject.com/term/data/1522775/)" icon by [Aybige](https://thenounproject.com/aybigeaya/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Exploit.svg`](src/main/resources/icons/Exploit.svg) | <img src="src/main/resources/icons/Exploit.svg" alt="Exploit.svg" width="32" height="32"/> "[Biohazard](https://thenounproject.com/term/biohazard/288075/)" icon by [lastspark](https://thenounproject.com/lastspark/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Identity.svg`](src/main/resources/icons/Identity.svg) | <img src="src/main/resources/icons/Identity.svg" alt="Identity.svg" width="32" height="32"/> "[identity card](https://thenounproject.com/term/identity-card/2894224/)" icon by [SBTS](https://thenounproject.com/sbts2018/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Information.svg`](src/main/resources/icons/Information.svg) | <img src="src/main/resources/icons/Information.svg" alt="Information.svg" width="32" height="32"/> "[Information](https://thenounproject.com/term/information/3267721/)" icon by [Vincencio](https://thenounproject.com/vincenciogilberto/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Network.svg`](src/main/resources/icons/Network.svg) | <img src="src/main/resources/icons/Network.svg" alt="Network.svg" width="32" height="32"/> "[Network](https://thenounproject.com/term/network/2580746/)" icon by [mardjoe](https://thenounproject.com/mereketeheloany/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`PhysicalZone.svg`](src/main/resources/icons/PhysicalZone.svg) | <img src="src/main/resources/icons/PhysicalZone.svg" alt="PhysicalZone.svg" width="32" height="32"/> "[Location](https://thenounproject.com/term/location/197119/)" icon by [Sergey Novosyolov](https://thenounproject.com/sergey.novosyolov/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`RoutingFirewall.svg`](src/main/resources/icons/RoutingFirewall.svg) | <img src="src/main/resources/icons/RoutingFirewall.svg" alt="RoutingFirewall.svg" width="32" height="32"/> "[Router](https://thenounproject.com/term/router/1602484/)" icon by [SBTS](https://thenounproject.com/sbts2018/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`System.svg`](src/main/resources/icons/System.svg) | <img src="src/main/resources/icons/System.svg" alt="System.svg" width="32" height="32"/> "[Server](https://thenounproject.com/term/server/3303099/)" icon by [Icons Field](https://thenounproject.com/iconsdream96/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`User.svg`](src/main/resources/icons/User.svg) | <img src="src/main/resources/icons/User.svg" alt="User.svg" width="32" height="32"/> "[profile](https://thenounproject.com/term/profile/2027523/)" icon by [Gagana](https://thenounproject.com/gaganasaki10/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |
| [`Vulnerability.svg`](src/main/resources/icons/Vulnerability.svg) | <img src="src/main/resources/icons/Vulnerability.svg" alt="Vulnerability.svg" width="32" height="32"/> "[Shield broken](https://thenounproject.com/term/shield-broken/303944/)" icon by [Yuri Mazursky](https://thenounproject.com/colo/) from [the Noun Project](https://thenounproject.com/) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). |

See [`LICENSE`](LICENSE) and [`NOTICE`](NOTICE) for details.

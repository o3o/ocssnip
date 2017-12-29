# ocssnip - my UltiSnips snippets for CSharp

ocssnip is a collection of [UltiSnips](https://github.com/SirVer/ultisnips) snippets for the C# programming language

## Getting Started
* Install [UltiSnips](https://github.com/SirVer/ultisnips#quick-start)
* Get ocssnip: `git clone https://github.com/o3o/ocssnip.git`
* Copy the `cs.snippets` file to UltiSnips user snippets directory. On Linux this
  should be `~/.vim/UltiSnips`.


## References
### Language
|        |                            |
| ---    | -----                      |
| `len`  | length                     |
| `nimp` | NotImplementedException    |
| `pr`   | private readonly           |
| `priv` | private                    |
| `pub`  | public                     |
| `pubv` | public void                |
| `ret`  | return                     |
| `rett` | return /*value to return*/ |
| `ro`   | readonly                   |
| `vd`   | void                       |
| `wr`   | Console.WriteLine          |

### Strings
|         |                 |
| ---     | -----           |
| `stre`  | string.Empty    |
| `strf`  | string.Format() |
| `strne` | IsNullOrEmpty() |
| `ts`    | ToString()      |

### Branches
|        |                            |
| ---    | -----                      |
| `case` | case /*value*/:  break     |
| `el`   | else {                     |
| `elif` | else if (/*condition*/)    |
| `if`   | if (/*condition*/)         |
| `ife`  | if (/*condition*/) else    |
| `ifnn` | if (/*condition*/ != null) |
| `sw`   | switch (/*var*/) .. case   |

### Loops
|           |                                                 |
| ---       | -----                                           |
| `do`      | do while                                        |
| `for`     | for (/*type*/ i = 0; i < count; ++i)            |
| `fore`    | foreach (/*elem*/; /*range*/)                   |
| `fori`    | for (int i = 0; i < count; ++i)                 |
| `wh`      | while (/*condition*/)                           |

### Type definitions
|          |           |
| ---      | -----     |
| `class`  | class     |
| `enum`   | enum      |
| `inter`  | interface |
| `struct` | struct    |

### Functions
|           |                                            |
| ---       | -----                                      |
| `fun`     | /*ret*/ /*function name*/(/*args*/)        |
| `func`    | void /*function name*/(/*args*/)           |
| `funp`    | public /*ret*/ /*function name*/(/*args*/) |
| `get`     | *getter property*                          |
| `getset`  | *getter setter property*                   |
| `getsetf` | *getter setter property full*              |
| `main`    | void main(string[] args)                   |
| `maini`   | int main(string[] args)                    |


### Using
|            |                            |
| ---        | -----                      |
| `uscg`     | System.Collections.Generic |
| `unsub`    | NSubstitute                |
| `uautofix` | Ploeh.AutoFixture          |
| `ulinq`    | Linq                       |
| `ununit`   | NUnit.Framework            |

### Event
|           |                 |
| ---       | -----           |
| `event`   | Full declaraton |
| `evente`  | EventArgs.Empty |
| `eventon` | *On* Function   |

### Exception handling
|         |                         |
| ---     | -----                   |
| `try`   | try , catch             |
| `tryf`  | try , catch and finally |
| `catch` | catch (Exception e)     |
| `thr`   | throw new Exception()   |


### Comments
|        |                 |
| ---    | -----           |
| `fix`  | // FIX:         |
| `todo` | // TODO:        |
| `sdoc` | Short doc block |

### log4net
|         |             |
| ---     | -----       |
| `log`   | declaration |
| `logd`  | Debug       |
| `logdf` | DebugFormat |
| `logi`  | Info        |
| `logif` | InfoFormat  |
| `logw`  | Warn        |
| `logwf` | WarnFormat  |
| `loge`  | Error       |
| `logef` | ErrorFormat |
| `logf`  | Fatal       |
| `logff` | FatalFormat |

### NUnit
|            |                          |
| ---        | -----                    |
| `asempty`  | Is empty                 |
| `asf`      | Is false                 |
| `asgt`     | Is greater than          |
| `asgte`    | Is greater than or equal |
| `aslt`     | Is less than             |
| `aslte`    | Is less than or equal    |
| `asnempty` | Is not empty             |
| `asnnull`  | Is not null              |
| `asnull`   | Is null                  |
| `ast`      | Is true                  |
| `asth`     | Assert throw             |
| `aseq`     | Assert is equal          |
| `asneq`    | Assert is not equal      |
| `exp`      | Explicit                 |
| `ignore`   | Ignore                   |
| `setcul`   | Set culture              |
| `test`     | Test                     |
| `testcase` | Test case                |
| `testfix`  | Test fixture             |


### Ploeh.Autofixture
|              |                |
| ---          | -----          |
| `autonew`    | new Fixture    |
| `autocreate` | Create Fixture |

### Nsubstitue
|          |                   |
| ---      | -----             |
| `ssub`   | Substitute.For    |
| `sevent` | Raise.Event       |
| `sany`   | Arg.Any           |
| `sis`    | Arg.Is            |
| `sret`   | Returns           |
| `sreta`  | ReturnsForAnyArgs |
| `srec`   | Received          |
| `snrec`  | DidNotReceived    |

### Extensions (from Unstandard)

#### General
|         |                            |
| ---     | -----                      |
| `with`  | With(/*values*/)           |

#### Contracts
|         |                            |
| ---     | -----                      |
| `req`   | Guard condition            |
| `reqn`  | Requires not null          |
| `reqne` | Requires not null or empty |
| `reqt`  | Requires that              |
| `ensn`  | Ensures not null           |
| `ensne` | Ensures not null or empty  |
| `enst`  | Ensures that               |
| `ensnr` | Ensures not reached        |


#### Should
|        |                        |
| ---    | -----                  |
| `seq`  | ShouldEqual            |
| `sneq` | ShouldNotEqual(/*to*/) |
| `st`   | ShouldBeTrue           |
| `sf`   | ShouldBeFalse          |
| `sn`   | ShouldBeNull           |
| `snn`  | ShouldNotBeNull        |
| `sne`  | ShouldNotBeNullOrEmpty |

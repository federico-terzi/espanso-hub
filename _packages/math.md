---
package_name: "math"
package_title: "Math"
package_desc: "Mathematical symbols such as for Boolean and set operations"
package_version: "0.1.0"
package_author: "Dian M Fay"
package_original_repo: "https://github.com/dmfay/espanso-math"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A package containing some mathematical symbols such as for Boolean and set operations which aren't always readily available otherwise.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

#### Boolean

| Trigger    | Replace with |
|  ----      |    ----      |
| `:and`     | `∧`          |
| `:or`      | `∨`          |
| `:xor`     | `⩛`          |

#### Proposition

| Trigger    | Replace with |
|  ----      |    ----      |
| `:not`     | `¬`          |
| `:impl`    | `⇒`          |
| `:equiv`   | `⇔`          |

#### Set

| Trigger        | Replace with |
|  ----          |    ----      |
| `:forall`      |   `∀`        |
| `:exist`       |   `∃`        |
| `:inset`       |   `∈`        |
| `:notin`       |   `∉`        |
| `:niset`       |   `∋`        |
| `:notni`       |   `∌`        |
| `:subset`      |   `⊂`        |
| `:subseq`      |   `⊆`        |
| `:supset`      |   `⊃`        |
| `:supseq`      |   `⊇`        |
| `:union`       |   `∪`        |
| `:intersect`   |   `∩`        |

#### Proof

| Trigger      | Replace with |
|  ----        |    ----      |
| `:therefore` | `∴`          |
| `:because`   | `∵`          |
| `:qed`       | `■`          |

#### Miscellaneous

| Trigger     | Replace with |
|  ----       |    ----      |
| `:cong`     | `≅`          |
| `:sqrt`     | `√`          |
| `:approx`   | `≈`          |
| `:sum`      | `∑`          |
| `:integral` | `∫`          |
| `:dagger`   | `†`          |


## Package Details

Repository: <{{ page.package_original_repo }}>

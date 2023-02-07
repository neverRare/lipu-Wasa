## ilo Wasa o lon

pali nanpa wan li ni: o lon e nasin Wasa lon ilo sina kepeken ilo `rustup`. ilo `rustup` li lon e ilo mute pi nasin Wasa. ni la ilo sina o ken toki tawa ilo ante.

> sina wile ala kepeken ilo `rustup` la o lukin e lipu ni: [Other Rust Installation Methods page][otherinstall]

lipu ni li toki e nasin ni: sina jo e ilo sin a pi nasin Wasa.

ilo pi nasin Wasa li tan tenpo ni anu tenpo kama la ilo li ken sona e nasin Wasa pi lipu ni. taso, ken la, ilo li toki e ijo ante tan lipu ni. ni li tan ni: mama pi nasin Wasa li pona e ilo lon tenpo ale.

> ### sitelen pi toki ilo
>
> lipu ni la toki ilo li lon. toki sina la sitelen `$` li lon open. sina o toki ala e sitelen `$`. toki pi sitelen `$` ala li toki tan ilo. ante la, ilo Pawase la, sitelen `>` li lon. kin sitelen `$` li lon ala.

### nasin pi ilo Linu anu ilo Makowe

sina kepeken ilo Linu anu ilo Makowe la o toki e ni tawa ilo:

```console
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

kepeken toki ni la ilo `rustup` li kama lon. ken la, sina wile toki len. kepeken toki len ni la ilo sina li ken sona e ni: jan ilo li sina.

kama lon li pona la sina ken lukin e ni:

```text
Rust is installed now. Great!
```

ilo li wile e ilo pi nasin Si. ken la, ilo li jo e ona.

ilo Makowe la ilo li ken jo e ilo ni kepeken toki ni:

```console
$ xcode-select --install
```

ilo Linu la ilo o jo e ilo Sisisi anu ilo Kalan.

ilo Upuntu la ilo o jo e ilo `build-essential` tan ilo `apt`.

### nasin pi ilo Winto

o tawa [lipu https://www.rust-lang.org/tools/install][install]. o kute e toki ilo.

ilo li wile e ilo MSVC Build Tools. o lon e [ilo Visual Studio 2022][visualstudio]. ilo ni li toki e wile sina la o jo e ni:

* “Desktop Development with C++”
* The Windows 10 or 11 SDK
* The English language pack component; sina ken jo e toki sina.

toki ilo pi lipu ni la sina ken kepeken ilo *cmd.exe* anu ilo Pawase. sina wile kepeken wan la lipu ni li toki e ni.

### pakala la

ijo li pakala la o sona e ni: ilo pi nasin Wasa li lon ala lon pona? o alasa kepeken toki ni:

```console
$ rustc --version
```

ilo li toki sama sitelen ni la, ilo li lon pona.

```text
rustc x.y.z (abcabcabc yyyy-mm-dd)
```

sitelen ni li lon ala la o sona e ni: ilo pi nasin Wasa li lon ala kulupu `%PATH%`?

ilo Winto la ilo CMD la sina ken sona kepeken toki ni:

```console
> echo %PATH%
```

ilo Winto la ilo Pawase la sina ken sona kepeken toki ni:

```powershell
> echo $env:Path
```

ilo Linu anu ilo Makowe la sina ken sona kepeken toki ni:

```console
$ echo $PATH
```

ijo li awen pakala la [o toki tawa kulupu Wasa][community].

### nasin pi jo sin en nasin weka

sina wile jo e ilo sin la o toki e ni:

```console
$ rustup update
```

sina wile weka e ilo pi nasin Wasa la o toki e ni:

```console
$ rustup self uninstall
```

### lipu tan ilo `rustup`

ilo li jo e lipu ale pi nasin Wasa. sina wile lukin e ni la o toki e ni:

```console
$ rustup doc
```

ni la lipu li kama lon ilo sina. sina wile sona e ijo pi nasin Wasa la o ni!

[otherinstall]: https://forge.rust-lang.org/infra/other-installation-methods.html
[install]: https://www.rust-lang.org/tools/install
[visualstudio]: https://visualstudio.microsoft.com/downloads/
[community]: https://www.rust-lang.org/community

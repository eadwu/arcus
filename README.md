<div align="center">
  <p>
    <span>
      <b>arcus</b>
    </span>
    <br />
    Unofficial Arch Repository
  </p>

  <p>
    <a href="https://gitlab.com/eadwu/arcus/commits/master">
      <img src="https://gitlab.com/eadwu/arcus/badges/master/pipeline.svg" />
    </a>
    <a href="https://www.archlinux.org">
      <img src="https://img.shields.io/badge/OS-Arch_Linux-1793D1.svg" />
    </a>
  </p>
</div>

---

  - [Getting started](#getting-started)
    - [Integration](#integration)
      - [Add the repository](#add-the-repository)
  - [License](#license)

## Getting started
### Integration
#### Add the repository
In `/etc/pacman.conf`, add the following code:
```
[arcus]
SigLevel = PackageOptional
Server = https://eadwu.gitlab.io/arcus/repo/x86_64
```
and then run `[sudo] pacman -Syy` to refresh the package lists with `[sudo] pacman -Syu` to upgrade the system.

---

## License

<div align="center">
  <p>Copyright &copy; 2018 Edmund Wu</p>

  <p>
    <a>
      <img src="https://img.shields.io/badge/License-BSD--3--Clause-5E81AC.svg" />
    </a>
  </p>
</div>

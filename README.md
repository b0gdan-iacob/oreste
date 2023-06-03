# oreste

## What is the oreste

Oreste is yet another OSINT Tool for research porposes only. It allows you to gather information about the target via email, phone or image and generate an report.

#### Features: :eyes:

- Email validation
- Check social accounts
- Check data breaches and password leaks
- Find related emails and domains
- Scan Pastebin Dumps
- Google Search
- DNS/IP Lookup
- Google Dorks
- Phone Registries
- Reverse Image Search

## Services (APIs):

| Service                                         | Function                      | Status                   |
| :---------------------------------------------- | :---------------------------- | :----------------------- |
| [ipapi.co](https://ipapi.co/) - Public          | More Information About Domain | :white_check_mark:       |
| [hunter.io](https://hunter.io/) - Public        | Related Emails                | :white_check_mark: :key: |
| [emailrep.io](https://emailrep.io/) - Public    | Breached Sites Names          | :white_check_mark: :key: |
| [scylla.so](https://scylla.so/) - Public        | Database Leaks                | :construction:           |
| [psbdmp.ws](https://psbdmp.ws/) - Public        | Pastebin Dumps                | :white_check_mark: :key: |
| [Intelligence X](https://intelx.io/)            | Password Leaks                | :white_check_mark: :key: |
| [BreachDirectory](https://breachdirectory.org/) | Password Leaks                | :white_check_mark: :key: |

:key: API key required

#### If you want to use oreste with full features, set your API keys:

```
 oreste set hunter <hunter.io API key>
 oreste set emailrep <emailrep.io API key>
 oreste set intelx <intelx.io API key>
 oreste set psbdmp <psbdmp.ws API key>
 oreste set breachdirectory <breachdirectory.org API key>
```

## Installation:

```
go install -v github.com/alpkeskin/oreste@latest
```

## Usage:

Email(mosint):

```
oreste example@email.com
```

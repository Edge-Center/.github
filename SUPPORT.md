# Getting help

Pick the channel that matches what you need. It gets you an answer faster and
keeps the issue trackers usable.

## The code in this organization

Bugs, unexpected behavior and feature requests for the Terraform provider, the
Go SDKs, the Kubernetes components and the plugins go into the issue tracker of
the repository they belong to. Use the templates - a version number and a
reproducer are what turn a report into a fix.

Before filing:

- Check the existing issues, including closed ones.
- Reproduce on the latest release. A large share of reports are already fixed.
- For the Terraform provider, attach the plan or apply output and the relevant
  part of the configuration with credentials removed.

## The EdgeCenter platform

Anything about your account, billing, quotas, a region being unavailable, or the
API behaving differently from its documentation is a platform question, not a
repository question. Use the support channels in the
[EdgeCenter control panel](https://edgecenter.ru) and the
[knowledge base](https://edgecenter.ru/knowledge-base).

## Documentation

- [Terraform Registry](https://registry.terraform.io/providers/Edge-Center/edgecenter/latest) -
  reference for every resource and data source.
- [API reference](https://apidocs.edgecenter.ru) - the endpoints the SDKs wrap.
- [Knowledge base](https://edgecenter.ru/knowledge-base) - product guides.
- [pkg.go.dev](https://pkg.go.dev/github.com/Edge-Center/edgecentercloud-go/v2) -
  Go SDK reference.

## Security problems

Never in a public issue. See [SECURITY.md](SECURITY.md).

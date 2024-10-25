# Understanding YAML Bindings.
- Refer the offical [yaml spec](https://yaml.org/spec/) and the [yaml specification for dotrain](https://github.com/rainlanguage/specs/blob/main/ob-yaml.md). The provided front matter coupled with specific rainlang is directly parsed, composed and bound by the dotrain tooling, different binding result in different compositions. 
- The document specifies the raindex app version that was used to parse the fragement into a rainlang document. The resultant composition of the document depends upon the tooling with which the document is tied, so it is imperative that the fragement mentions the raindex version so that the tooling that comes with that particular version is used for the resultant composition.
```
raindex-version : db14c87f012a76980661802ff424371d6e84552e
```
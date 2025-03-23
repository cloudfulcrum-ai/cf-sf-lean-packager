# Lean Packager

**cf-sf-lean-packager**

    Packages and prepares Salesforce metadata for deployment.

* **Inputs**:
    * **source-directory**: Path to metadata source files.
    * **package-name**: Name of the package to be created.


* **Outputs**:
    * **package-path**: Path to the generated package.

Usage Example:

    - name: Package Salesforce Metadata
      uses: ghcr.io/itfulcrum/cf-sf-lean-packager@latest
      with:
          source-directory: "./src"
          package-name: "MyPackage.zip"

## Installation & Usage

To use these GitHub Actions, ensure that your repository has:

* A .github/workflows/ directory for defining workflows.
* Necessary Salesforce authentication secrets configured in GitHub Actions.

## Contributing

Feel free to submit pull requests to improve existing actions or add new functionality.

## License

This project is licensed under the MIT License.

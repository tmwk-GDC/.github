# Ohayo ✌️
<!-- vscode-markdown-toc -->
* 1. [Create a new repository](#Createanewrepository)
* 2. [Template Terraform](#TemplateTerraform)
	* 2.1. [How to use this?](#Howtousethis)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->
<!-- generate by https://marketplace.visualstudio.com/items?itemName=joffreykern.markdown-toc> -->

<dl>
	<p align="center">
		<img width="640" alt="gdc" src="../img/gdc_github_10fps.640x224.gif">
	</p>
  <p align="center">
		Built with ❤️ by GDC Team 🦄 .
	</p>
</dl>

##  1. <a name='Createanewrepository'></a>Create a new repository

If you need to create a new repository for a customer or a project, please, follow these convention:

- Inspired by ModernApp: [`internal/clients`]-`<client-name>`-`<project>`-[`<sub-project/extra-string>`]
  - internal-teamwork-demo-usf-2024-ai
  - clients-gallery44-vintage-sourcing
  - internal-gdc-cloud-home-page
  - ...

- Inspired by ModernPlatforms: `<customer>`-`<project>`-[`<sub-project/extra-string>`]
  - teamwork-app1
  - mycustomerA-landing-zone-network
  - mycustomerB-sap-dev
  - ...

##  2. <a name='TemplateTerraform'></a>Template Terraform

ModernPlatform has provided two templates (AWS/Azure) to deliver Terraform code via a common CI/CD (thanks @SamuelRochcongar).
- [template-aws-project](https://github.com/tmwk-ModernPlatforms/template-aws-project)
- [template-azure-project](https://github.com/tmwk-ModernPlatforms/template-azure-project)

###  2.1. <a name='Howtousethis'></a>How to use this?

1. Choose your template.
2. On you right, select `Use this template`.
3. In `Owner` select your organizations.
4. Git it a name 🙃.
5. Validate by `Create repository`.
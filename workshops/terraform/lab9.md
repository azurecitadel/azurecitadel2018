---
layout: article
title: "Terraform Lab 9: Provisioners"
categories: null
date: 2018-08-01
tags: [azure, terraform, modules, infrastructure, paas, iaas, code]
comments: true
author: Richard_Cheney
published: false
---

{% include toc.html %}

## Introduction

In this lab we will look at provisioners, and how they can be used to drive additional virtual machine customisation once the base image has been deployed.

We will also look at templates in the context of Terraform, and how you can use variables to customise the creation of text files on your servers.

## End of Lab 9

We have reached the end of the lab. You have use provisioners and templates to demonstrate how you could direc additiopnal configuration in your virtual machines once they have been deployed from a template.

Your .tf files should look similar to those in <https://github.com/richeney/terraform-lab9>.

In the next lab we will look at one of the other Hashicorp products that complements this area, and how you can use Packer to programmatically create custom images to underpin your Azure virtual machine deployments.

[◄ Lab 8: Extending](../lab8){: .btn-subtle} [▲ Index](../#labs){: .btn-subtle} [Lab 10: Packer ►](../lab10){: .btn-success}

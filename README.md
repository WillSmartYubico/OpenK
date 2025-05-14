# :warning: Warning

Don't use this.  Don't use it for security, don't use it for conveniece.  It has
been purposefully broken in ways that make it dangerous for reasons that should
be obvious, and also possibly accidentially broken in ways that aren't 
understood.

This is not an officially supported Yubico product.

This is not an officially supported Google product.

This project is **proof-of-concept and a research platform**. It is **NOT**
meant for a daily usage.

## OpenK

This repository contains a fork of OpenSK, a Rust implementation of a
[FIDO2](https://fidoalliance.org/fido2/) security key.
Security keys are external devices that can be used for signing in on websites.
You can see OpenSK in action in this
[video on YouTube](https://www.youtube.com/watch?v=klEozvpw0xg)!

This fork is intended to help break the mindset that synced passkeys represent 
some sort of sea change in the security model of WebAuthn, and opens up some 
avenues for some automated testing scenarios.

For general information about the excellent OpenSK project this work is based 
on, visit https://github.com/google/opensk

## Using this repository & branch structure

If normal software projects use feature branches, this repository uses *defect* 
branches.  Some effort will be made to ensure each defect branch is modular, but 
nothing in this project is guaranteed.

To use theis repository, first fork it, and then create a new branch based off 
of "develop".  Then, merge in each of the defect branches for the defects you 
want to introduce.

Optionally, merge in the nrfutil branch if you're using a newer version of the 
nrfutil binary that doesn't support the version subcommand.

Finally, build the project as documented in the original OpenSK project.

## Reporting a Vulnerability

Don't.  This project is all vulnerabilities.

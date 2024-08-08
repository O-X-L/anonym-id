# Anonym ID

This is a feature-draft.

If you are intested in discussing this idea - feel free to [open a discussion](https://github.com/O-X-L/anonym-id/discussions).


## Basic Features


`Verified personal ID <=> Anonym ID Service <=> Signing Content/Validating Signatures`

* Proxy for User Identification

* Apps can add this service to their User interfaces, so the content they consume if validated in realtime

* Usecase: Anti AI-Generated Deepfakes

A service like this CANNOT be hosted administered by governments, nor companies - as they might be currupted and abuse their power.

----


## Signing Content

The service could provide a way of signing content using the users Anonym-ID.

This content can be verified to be from a specific source.


### Public Identity

If the user chooses to make their identity public, it will be shown when validating the content signatures.

The identity can be personal or an entity.

Per example: `Validated: John Doe` or `Validated: Super Company AG`

Of course: When registering those identities, the documents need to match them.


### Anonymouns

In this case the user only uses the generic Anonym-ID signature.

A comment might be allowed. (*for online usernames and so on*)

Per example: `Validated: c8c53983-84b9-4120-b4a4-bba3e866566b (UserXYZ)`


----

## Registering Identity

If the user wants to stay anonymous:

* Their personal information is not stored after the validation process finished

* Their identity could be stored only as hash (anti duplicate ID)

### Link via Government ID-Services

Some governments already provide digital IDs to their citzens. (p.e. [ID Austria](https://www.oesterreich.gv.at/id-austria.html))

The service could validate the identity by linking to those services.


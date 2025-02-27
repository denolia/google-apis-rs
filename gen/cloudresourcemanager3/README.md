<!---
DO NOT EDIT !
This file was generated automatically from 'src/generator/templates/api/README.md.mako'
DO NOT EDIT !
-->
The `google-cloudresourcemanager3` library allows access to all features of the *Google Cloud Resource Manager* service.

This documentation was generated from *Cloud Resource Manager* crate version *5.0.2+20230115*, where *20230115* is the exact revision of the *cloudresourcemanager:v3* schema built by the [mako](http://www.makotemplates.org/) code generator *v5.0.2*.

Everything else about the *Cloud Resource Manager* *v3* API can be found at the
[official documentation site](https://cloud.google.com/resource-manager).
# Features

Handle the following *Resources* with ease from the central [hub](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/CloudResourceManager) ... 

* [effective tags](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::EffectiveTag)
 * [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::EffectiveTagListCall)
* [folders](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::Folder)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderDeleteCall), [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderGetCall), [*get iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderGetIamPolicyCall), [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderListCall), [*move*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderMoveCall), [*patch*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderPatchCall), [*search*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderSearchCall), [*set iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderSetIamPolicyCall), [*test iam permissions*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderTestIamPermissionCall) and [*undelete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::FolderUndeleteCall)
* [liens](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::Lien)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::LienCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::LienDeleteCall), [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::LienGetCall) and [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::LienListCall)
* [operations](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::Operation)
 * [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OperationGetCall)
* [organizations](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::Organization)
 * [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OrganizationGetCall), [*get iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OrganizationGetIamPolicyCall), [*search*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OrganizationSearchCall), [*set iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OrganizationSetIamPolicyCall) and [*test iam permissions*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::OrganizationTestIamPermissionCall)
* [projects](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::Project)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectDeleteCall), [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectGetCall), [*get iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectGetIamPolicyCall), [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectListCall), [*move*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectMoveCall), [*patch*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectPatchCall), [*search*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectSearchCall), [*set iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectSetIamPolicyCall), [*test iam permissions*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectTestIamPermissionCall) and [*undelete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::ProjectUndeleteCall)
* [tag bindings](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagBinding)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagBindingCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagBindingDeleteCall) and [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagBindingListCall)
* [tag keys](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKey)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyDeleteCall), [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyGetCall), [*get iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyGetIamPolicyCall), [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyListCall), [*patch*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyPatchCall), [*set iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeySetIamPolicyCall) and [*test iam permissions*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagKeyTestIamPermissionCall)
* [tag values](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValue)
 * [*create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueCreateCall), [*delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueDeleteCall), [*get*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueGetCall), [*get iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueGetIamPolicyCall), [*list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueListCall), [*patch*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValuePatchCall), [*set iam policy*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueSetIamPolicyCall), [*tag holds create*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueTagHoldCreateCall), [*tag holds delete*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueTagHoldDeleteCall), [*tag holds list*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueTagHoldListCall) and [*test iam permissions*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/api::TagValueTestIamPermissionCall)




# Structure of this Library

The API is structured into the following primary items:

* **[Hub](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/CloudResourceManager)**
    * a central object to maintain state and allow accessing all *Activities*
    * creates [*Method Builders*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::MethodsBuilder) which in turn
      allow access to individual [*Call Builders*](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::CallBuilder)
* **[Resources](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Resource)**
    * primary types that you can apply *Activities* to
    * a collection of properties and *Parts*
    * **[Parts](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Part)**
        * a collection of properties
        * never directly used in *Activities*
* **[Activities](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::CallBuilder)**
    * operations to apply to *Resources*

All *structures* are marked with applicable traits to further categorize them and ease browsing.

Generally speaking, you can invoke *Activities* like this:

```Rust,ignore
let r = hub.resource().activity(...).doit().await
```

Or specifically ...

```ignore
let r = hub.folders().create(...).doit().await
let r = hub.folders().delete(...).doit().await
let r = hub.folders().move_(...).doit().await
let r = hub.folders().patch(...).doit().await
let r = hub.folders().undelete(...).doit().await
let r = hub.operations().get(...).doit().await
let r = hub.projects().create(...).doit().await
let r = hub.projects().delete(...).doit().await
let r = hub.projects().move_(...).doit().await
let r = hub.projects().patch(...).doit().await
let r = hub.projects().undelete(...).doit().await
let r = hub.tag_bindings().create(...).doit().await
let r = hub.tag_bindings().delete(...).doit().await
let r = hub.tag_keys().create(...).doit().await
let r = hub.tag_keys().delete(...).doit().await
let r = hub.tag_keys().patch(...).doit().await
let r = hub.tag_values().tag_holds_create(...).doit().await
let r = hub.tag_values().tag_holds_delete(...).doit().await
let r = hub.tag_values().create(...).doit().await
let r = hub.tag_values().delete(...).doit().await
let r = hub.tag_values().patch(...).doit().await
```

The `resource()` and `activity(...)` calls create [builders][builder-pattern]. The second one dealing with `Activities` 
supports various methods to configure the impending operation (not shown here). It is made such that all required arguments have to be 
specified right away (i.e. `(...)`), whereas all optional ones can be [build up][builder-pattern] as desired.
The `doit()` method performs the actual communication with the server and returns the respective result.

# Usage

## Setting up your Project

To use this library, you would put the following lines into your `Cargo.toml` file:

```toml
[dependencies]
google-cloudresourcemanager3 = "*"
serde = "^1.0"
serde_json = "^1.0"
```

## A complete example

```Rust
extern crate hyper;
extern crate hyper_rustls;
extern crate google_cloudresourcemanager3 as cloudresourcemanager3;
use cloudresourcemanager3::api::TagKey;
use cloudresourcemanager3::{Result, Error};
use std::default::Default;
use cloudresourcemanager3::{CloudResourceManager, oauth2, hyper, hyper_rustls, chrono, FieldMask};

// Get an ApplicationSecret instance by some means. It contains the `client_id` and 
// `client_secret`, among other things.
let secret: oauth2::ApplicationSecret = Default::default();
// Instantiate the authenticator. It will choose a suitable authentication flow for you, 
// unless you replace  `None` with the desired Flow.
// Provide your own `AuthenticatorDelegate` to adjust the way it operates and get feedback about 
// what's going on. You probably want to bring in your own `TokenStorage` to persist tokens and
// retrieve them from storage.
let auth = oauth2::InstalledFlowAuthenticator::builder(
        secret,
        oauth2::InstalledFlowReturnMethod::HTTPRedirect,
    ).build().await.unwrap();
let mut hub = CloudResourceManager::new(hyper::Client::builder().build(hyper_rustls::HttpsConnectorBuilder::new().with_native_roots().https_or_http().enable_http1().enable_http2().build()), auth);
// As the method needs a request, you would usually fill it with the desired information
// into the respective structure. Some of the parts shown here might not be applicable !
// Values shown here are possibly random and not representative !
let mut req = TagKey::default();

// You can configure optional parameters by calling the respective setters at will, and
// execute the final call using `doit()`.
// Values shown here are possibly random and not representative !
let result = hub.tag_keys().patch(req, "name")
             .validate_only(true)
             .update_mask(&Default::default())
             .doit().await;

match result {
    Err(e) => match e {
        // The Error enum provides details about what exactly happened.
        // You can also just use its `Debug`, `Display` or `Error` traits
         Error::HttpError(_)
        |Error::Io(_)
        |Error::MissingAPIKey
        |Error::MissingToken(_)
        |Error::Cancelled
        |Error::UploadSizeLimitExceeded(_, _)
        |Error::Failure(_)
        |Error::BadRequest(_)
        |Error::FieldClash(_)
        |Error::JsonDecodeError(_, _) => println!("{}", e),
    },
    Ok(res) => println!("Success: {:?}", res),
}

```
## Handling Errors

All errors produced by the system are provided either as [Result](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Result) enumeration as return value of
the doit() methods, or handed as possibly intermediate results to either the 
[Hub Delegate](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Delegate), or the [Authenticator Delegate](https://docs.rs/yup-oauth2/*/yup_oauth2/trait.AuthenticatorDelegate.html).

When delegates handle errors or intermediate values, they may have a chance to instruct the system to retry. This 
makes the system potentially resilient to all kinds of errors.

## Uploads and Downloads
If a method supports downloads, the response body, which is part of the [Result](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Result), should be
read by you to obtain the media.
If such a method also supports a [Response Result](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::ResponseResult), it will return that by default.
You can see it as meta-data for the actual media. To trigger a media download, you will have to set up the builder by making
this call: `.param("alt", "media")`.

Methods supporting uploads can do so using up to 2 different protocols: 
*simple* and *resumable*. The distinctiveness of each is represented by customized 
`doit(...)` methods, which are then named `upload(...)` and `upload_resumable(...)` respectively.

## Customization and Callbacks

You may alter the way an `doit()` method is called by providing a [delegate](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Delegate) to the 
[Method Builder](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::CallBuilder) before making the final `doit()` call. 
Respective methods will be called to provide progress information, as well as determine whether the system should 
retry on failure.

The [delegate trait](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Delegate) is default-implemented, allowing you to customize it with minimal effort.

## Optional Parts in Server-Requests

All structures provided by this library are made to be [encodable](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::RequestValue) and 
[decodable](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::ResponseResult) via *json*. Optionals are used to indicate that partial requests are responses 
are valid.
Most optionals are are considered [Parts](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::Part) which are identifiable by name, which will be sent to 
the server to indicate either the set parts of the request or the desired parts in the response.

## Builder Arguments

Using [method builders](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::CallBuilder), you are able to prepare an action call by repeatedly calling it's methods.
These will always take a single argument, for which the following statements are true.

* [PODs][wiki-pod] are handed by copy
* strings are passed as `&str`
* [request values](https://docs.rs/google-cloudresourcemanager3/5.0.2+20230115/google_cloudresourcemanager3/client::RequestValue) are moved

Arguments will always be copied or cloned into the builder, to make them independent of their original life times.

[wiki-pod]: http://en.wikipedia.org/wiki/Plain_old_data_structure
[builder-pattern]: http://en.wikipedia.org/wiki/Builder_pattern
[google-go-api]: https://github.com/google/google-api-go-client

# License
The **cloudresourcemanager3** library was generated by Sebastian Thiel, and is placed 
under the *MIT* license.
You can read the full text at the repository's [license file][repo-license].

[repo-license]: https://github.com/Byron/google-apis-rsblob/main/LICENSE.md


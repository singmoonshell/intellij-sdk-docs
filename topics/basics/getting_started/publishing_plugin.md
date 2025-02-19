[//]: # (title: Publishing a Plugin)

<!-- Copyright 2000-2022 JetBrains s.r.o. and other contributors. Use of this source code is governed by the Apache 2.0 license that can be found in the LICENSE file. -->

When your plugin is ready, you can publish it to a plugin repository so that other users can install it.
You can choose to publish it on the [JetBrains Marketplace](https://plugins.jetbrains.com) or a [custom plugin repository](update_plugins_format.md).

> Please see [Marketing](marketing.md) for remarks on how to prepare your plugin for optimal presentation.
>
{type="tip"}

Before publishing your plugin, make sure it is signed.
For more details on generating a proper certificate and configuring the signing process, check the [Plugin Signing](plugin_signing.md) article.

## Publishing to JetBrains Marketplace

<procedure title="Creating JetBrains Account">

To upload your plugin to the [JetBrains Marketplace](https://plugins.jetbrains.com), you must log in with your personal JetBrains Account.

1. Open the [JetBrains Account Center](https://account.jetbrains.com) and click <control>Create Account</control>.
2. Fill in all fields in the <control>Create JetBrains Account</control> form that opens and click <control>Register</control>.

</procedure>

<procedure title="Uploading plugin">

To upload your plugin to the JetBrains Plugins Repository:

1. [Log in to JetBrains Marketplace](https://plugins.jetbrains.com/author/me) with your personal JetBrains account.
2. On your Profile page that opens, click <control>Add new plugin</control>.
3. Fill in the <control>Add new plugin</control> form that opens and click the <control>Add the plugin</control> button to upload your plugin.

See also [Marketplace Docs](https://plugins.jetbrains.com/docs/marketplace/uploading-a-new-plugin.html).

</procedure>

### Uploading a New Version

When using Gradle, use the provided tasks as described in [](deployment.md).

New versions can be uploaded manually on the plugin's detail page, see [Marketplace Docs](https://plugins.jetbrains.com/docs/marketplace/custom-release-channels.html) for details.

## Publishing a Plugin to a Custom Plugin Repository

If you plan to publish your plugin to a repository _other than_ the [JetBrains Marketplace](https://plugins.jetbrains.com), please refer to the [Publishing to Custom Plugin Repositories](update_plugins_format.md) documentation.

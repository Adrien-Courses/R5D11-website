+++
categories = ["howto"]
description = "Configure the header and footer"
options = ["disableLandingPageButton", "landingPageName", "linkTitle", "showVisitedLinks"]
title = "Header & Footer"
weight = 2
+++

## Title

{{% badge style="cyan" icon="gears" title=" " %}}Option{{% /badge %}} With the [default partials](configuration/branding/logo#change-the-logo) for the logo, The site title will also be used for the text at the top of the sidebar. If you want to show a different text in the sidebar, you can overwrite `linkTitle`.

{{< multiconfig file=hugo >}}
[params]
  linkTitle = 'Relearn'
{{< /multiconfig >}}

## Home Button Configuration

By default, the theme displays a home button between search form and navigation menu. The Home button serves as an alternative to clicking the logo.

![Default Home Button](home_button_defaults.png?width=18.75rem)

{{% badge style="cyan" icon="gears" title=" " %}}Option{{% /badge %}} To hide the Home button on the left menu, set `disableLandingPageButton=true`.

{{< multiconfig file=hugo >}}
[params]
  disableLandingPageButton = true
{{< /multiconfig >}}

{{% badge style="cyan" icon="gears" title=" " %}}Option{{% /badge %}} To change its icon or text, configure the `landingPageName` for your defined languages.

{{< multiconfig file=hugo >}}
[languages]
  [languages.en]
    [languages.en.params]
      landingPageName = '<i class="fa-fw fas fa-home"></i> Home'

  [languages.pir]
    [languages.pir.params]
      landingPageName = '<i class="fa-fw fas fa-home"></i> Arrr! Homme'
{{< /multiconfig >}}

If this option isn't set for a specific language, it will use these default values

{{< multiconfig file=hugo >}}
[params]
  landingPageName = '<i class="fa-fw fas fa-home"></i> Home'
{{< /multiconfig >}}

## History

{{% badge style="cyan" icon="gears" title=" " %}}Option{{% /badge %}} Turn on `showVisitedLinks=true` to see checkmarks next to visited pages in the main menu. This also adds a `Clear History` option at the bottom of the menu to remove all checkmarks. Note that checkmarks will disappear if you rebuild your site, as the page IDs may change.

{{< multiconfig file=hugo >}}
[params]
  showVisitedLinks = true
{{< /multiconfig >}}

## Footer

To change the menu footer, edit the `layouts/partials/menu-footer.html` file. Check out the [Partials section](configuration/customization/partials) for more ways to customize your site.
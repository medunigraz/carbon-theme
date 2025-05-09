MedUniGraz theme for IBM Carbon
===============================

Usage
----

Install the package:

::

  npm install @medunigraz/carbon-theme

Use the provided theme in your global `styles.scss` to configure the carbon theme system:

::

  @use '@medunigraz/carbon-theme/theme' as medunigraz;
  @use '@carbon/react/scss/theme' with (
    $theme: medunigraz.$default
  );

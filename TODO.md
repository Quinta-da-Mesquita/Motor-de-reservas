# Optimization Tasks for en-gb/mesquita.html

## Step 1: Clean up Head Section
- [ ] Remove unused <style> blocks: #customRules, #forceCssIncludes, #cssVariables, #fontFallbacks, #hideAnimFix, #globalFontSizeStyle, #pageFontSizeStyle, #pagestyleDevice, #innerPagesStyle, #additionalGlobalCss.
- [ ] Remove redundant scripts: deferred-init script, loadCSS function, some runtime props not essential.
- [ ] Keep: meta tags, title, canonical, OG, font links, essential CSS/JS includes, GTM.

## Step 2: Simplify HTML Structure in Body
- [ ] Remove excessive nested divs and unused IDs/classes that don't affect layout or JS (e.g., dmRespColsWrapper, dmRespCol IDs).
- [ ] Preserve navigation, iframes, footer structure.
- [ ] Remove redundant attributes: data- attributes not used for functionality, unused IDs/classes.

## Step 3: Clean up Inline Styles and CSS
- [ ] Remove inline styles in HTML elements that are redundant or not affecting visible formatting.
- [ ] Keep CSS that controls layout, colors, fonts.

## Step 4: Optimize Scripts in Body and End
- [ ] Remove unnecessary scripts: some deferred scripts, unused rtCommonProps, rtFlags.
- [ ] Keep: jQuery, analytics (GTM, GA), runtime core, essential tracking.

## Step 5: Preserve Core Elements
- [ ] Ensure booking iframe, map iframe, navigation links, footer text/links, logo, images are intact.
- [ ] Verify SEO elements are preserved.

## Step 6: Test and Verify
- [ ] After edits, check in browser for functionality.
- [ ] Confirm SEO tools recognize meta tags.

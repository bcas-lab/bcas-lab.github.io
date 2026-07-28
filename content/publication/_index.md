---
title: Publications

# Listing view
view: citation

# Optional banner image
banner:
  caption: ''
  image: ''
---

<script>
document.addEventListener('DOMContentLoaded', function () {
  const select = document.querySelector(
    'select.pubtype-select, select.pub-filters'
  );

  if (!select) return;

  const preferredOrder = [
    'article-journal',
    'international-conference',
    'domestic-conference',
    'book',
    '*'
  ];

  const options = Array.from(select.options);

  function getType(option) {
    const value = option.value || '';

    if (value === '*') return '*';

    return value
      .replace(/^\.pubtype-/, '')
      .replace(/^pubtype-/, '');
  }

  options.sort(function (a, b) {
    const aIndex = preferredOrder.indexOf(getType(a));
    const bIndex = preferredOrder.indexOf(getType(b));

    return (aIndex === -1 ? 999 : aIndex)
         - (bIndex === -1 ? 999 : bIndex);
  });

  options.forEach(function (option) {
    select.appendChild(option);
  });
});
</script>
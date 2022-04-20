# Elementor's PHP / JS hooks, both filter hooks and action hooks


### Elementor Init

https://developers.elementor.com/docs/hooks/elementor-init/

### Elementor Loaded

https://developers.elementor.com/docs/hooks/elementor-loaded/

### Add New Tabs

```php
function add_panel_tab() {
	\Elementor\Controls_Manager::add_tab(
		'new-tab',
		esc_html__( 'New Tab', 'plugin-name' )
	);
}
add_action( 'elementor/init', 'add_panel_tab' );
```

### Frontend Content

https://developers.elementor.com/docs/hooks/frontend-content/

### Render Frontend Elements

https://developers.elementor.com/docs/hooks/render-frontend-elements/

### Placeholder Image Filter Hooks

https://developers.elementor.com/docs/hooks/placeholder-image/

### Control Google Fonts Enqueue

https://developers.elementor.com/docs/hooks/print-google-fonts/

### Print Widget Template

https://developers.elementor.com/docs/hooks/print-widget-template/

### Render Widget Content

https://developers.elementor.com/docs/hooks/render-widget-content/

### Shape Dividers

https://developers.elementor.com/docs/hooks/shapes/

### Widget Skins

https://developers.elementor.com/docs/hooks/widget-skins/

### Save Editor Data

https://developers.elementor.com/docs/hooks/save-editor-data/

### Parse Element CSS

https://developers.elementor.com/docs/hooks/parse-element-css/

### Custom Query Filter

https://developers.elementor.com/docs/hooks/custom-query-filter/

### Injecting Controls

https://developers.elementor.com/docs/hooks/injecting-controls/

## JS Hooks

https://developers.elementor.com/docs/hooks/js/

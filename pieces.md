Control de la window:

```js
.add_plugins(DefaultPlugins.set(WindowPlugin {
            primary_window: Some(Window {
                resolution: WindowResolution::new(900., 700.).with_scale_factor_override(1.0),
                title: "Chess wars".into(),
                ..default()
            }),
            ..default()
        }))
```

---

database-plugin: basic

---

```yaml:dbfolder
name: Dieu Faerun
description: Liste des dieux de Faerun
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 0
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __tags__:
    key: __tags__
    id: __tags__
    input: metadata_tags
    label: File Tags
    accessorKey: __tags__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 0
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Campagne:
    input: text
    accessorKey: Campagne
    key: Campagne
    id: Campagne
    label: Campagne
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Tags:
    input: tags
    accessorKey: Tags
    key: Tags
    id: Tags
    label: Tags
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "race", value: "race", color: "hsl(261, 95%, 90%)"}
      - { label: "dieu", value: "dieu", color: "hsl(342,91%,42%)"}
      - { label: "nains", value: "nains", color: "hsl(165,61%,26%)"}
      - { label: "pantheon", value: "pantheon", color: "hsl(5,52%,26%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Alignement:
    input: text
    accessorKey: Alignement
    key: Alignement
    id: Alignement
    label: Alignement
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Domaine:
    input: text
    accessorKey: Domaine
    key: Domaine
    id: Domaine
    label: Domaine
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 202
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Influence:
    input: text
    accessorKey: Influence
    key: Influence
    id: Influence
    label: Influence
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 226
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Pantheon:
    input: text
    accessorKey: Pantheon
    key: Pantheon
    id: Pantheon
    label: Pantheon
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 199
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Symbole:
    input: text
    accessorKey: Symbole
    key: Symbole
    id: Symbole
    label: Symbole
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 472
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Plan:
    input: text
    accessorKey: Plan
    key: Plan
    id: Plan
    label: Plan
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 151
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: true
  source_data: tag
  source_form_result: "#dieu"
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 180
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```
eZMigrationBundle2 deprecations and backwards compatibility breaks
==================================================================

(intro...)

* service `ez_migration_bundle.complex_field.ezpage` has been removed, as upstream has dropped the ezpage field type

* config parameter `ez_migration_bundle.version_directory` was renamed to `ez_migration_bundle.version_directory`

* removed long-deprecated elements:
  - interface `API\LanguageAwareInterface`
  - class `Core\ComplexField\AbstractComplexField`
  - class `Core\ComplexField\ComplexFieldManager`
  - class `Core\Matcher\ContentMatcher\ContentResolver`
  - class `Core\ProcessBuilder`
  - class `Core\StorageHandler\Database`

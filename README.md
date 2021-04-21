# ESP32_LuatOS_Flashtool

## 1、rominfo

```json
{
	"type": "esp32",
	"bootloader_offset": "0x1000",
    "bootloader_file": "bootloader.bin",
    "partition_table_offset": "0x8000",
    "partition_table_file": "partition-table.bin",
    "otadata_offset": "0xe000",
    "otadata_file": "ota_data_initial.bin",
    "app_offset": "0x10000",
    "app_file": "luatos_esp32.bin",
    "spiffs_offset": "0xf0000",
    "spiffs_file": "demo.bin"
}
```

## 2、使用说明

lfs [lua_path]

生成脚本刷入文件

flash [COM] [baud] [firmware_path]

下载固件

pkg [build_path]

生成固件包
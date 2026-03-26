# View Metadata Tool (vmd)

This tool allows you to see metadata for any file, partition, and drive, 
as well as the specific block device, character device, FIFO, junction, mount point, socket, and symbolic link.

This tool will also allow you to put the metadata you aquire into a .JSON file, making it particularly useful for most use applications


---

# How to use

To use this metadata reader, you can type in the help command below to see the available options

```
vmd -h
```
---
**Example commands:**

```
vmd foo.txt
```
^^^ Shows metadata for file "foo.txt"

```
vmd foo.txt -j bar.json
```
^^^ Puts the metadata for "foo.txt" into a JSON file called "bar.json"

---
# Options
  ```
  -h, --help       Shows this help message and exit
  -j, --json JSON  Path to json file
  -m, --metric     Format size (metric)
  -q, --quiet      Quiet (no output)
  -v, --verbose    Show additional information
```

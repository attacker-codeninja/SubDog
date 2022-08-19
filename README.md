```

███████╗██╗   ██╗██████╗ ██████╗  ██████╗  ██████╗ 
██╔════╝██║   ██║██╔══██╗██╔══██╗██╔═══██╗██╔════╝ 
███████╗██║   ██║██████╔╝██║  ██║██║   ██║██║  ███╗
╚════██║██║   ██║██╔══██╗██║  ██║██║   ██║██║   ██║
███████║╚██████╔╝██████╔╝██████╔╝╚██████╔╝╚██████╔╝
╚══════╝ ╚═════╝ ╚═════╝ ╚═════╝  ╚═════╝  ╚═════╝  

```
       
# Description
subdog collect number of different sources to create a list of root subdomains (i.e.: corp.example.com)                                         

# Install
```
git clone https://github.com/rix4uni/subdog.git && cd subdog && chmod +x subdog && mv /usr/bin/
```

# Usage

**Scan a single domain**
```
subdog -d example.com
```

**By Default output saved ./ you can export file different location using -o**
```
subdog -d example.com -o <filename>
```

# Sources 
- [rapiddns](https://rapiddns.io)
- [threatminer](https://api.threatminer.org) 
- [riddler](https://riddler.io)
- [alienvault](https://otx.alienvault.com)
- [threatcrowd](https://www.threatcrowd.org)

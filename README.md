# Iniparser_reform
Fork and reform iniparser project ( https://github.com/ndevilla/iniparser.git ), and compose some APIs.

# An introduction to APIs
**Read string value:**
```cpp
read_profile_string(const char *section, const char *key, 
                    char *value, int size,const char *default_value, const char *file);
```

**Read int value:**
```cpp
read_profile_int(const char *section, const char *key, int default_value, const char *file);
```

**Set string value:**
```cpp
write_profile_string(const char *section, const char *key, const char *value, const char *file);
```


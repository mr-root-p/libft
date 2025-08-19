<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Libft - C Library</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            text-align: center;
            margin-bottom: 10px;
        }
        h2 {
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
            margin-top: 30px;
        }
        code {
            background-color: #ecf0f1;
            padding: 2px 6px;
            border-radius: 4px;
        }
        ul {
            margin-left: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .function {
            background-color: #dfe6e9;
            border-left: 4px solid #3498db;
            padding: 10px;
            margin: 5px 0;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <h1>Libft - C Library</h1>
    <p>Libft is a library containing a set of fundamental C functions, reimplementing some standard C library functions with additional utilities to simplify programming.</p>

    <div class="section">
        <h2>1. Character Functions</h2>
        <div class="function"><code>ft_isalpha(int c)</code> : Checks if the character is alphabetic (a-z, A-Z).</div>
        <div class="function"><code>ft_isdigit(int c)</code> : Checks if the character is a digit (0-9).</div>
        <div class="function"><code>ft_isalnum(int c)</code> : Checks if the character is alphanumeric.</div>
        <div class="function"><code>ft_isascii(int c)</code> : Checks if the character is in the ASCII table.</div>
        <div class="function"><code>ft_isprint(int c)</code> : Checks if the character is printable.</div>
        <div class="function"><code>ft_tolower(int c)</code> : Converts uppercase to lowercase.</div>
        <div class="function"><code>ft_toupper(int c)</code> : Converts lowercase to uppercase.</div>
    </div>

    <div class="section">
        <h2>2. String Functions</h2>
        <div class="function"><code>ft_strlen(const char *s)</code> : Returns the length of the string.</div>
        <div class="function"><code>ft_strchr(const char *s, int c)</code> : Finds the first occurrence of a character in a string.</div>
        <div class="function"><code>ft_strrchr(const char *s, int c)</code> : Finds the last occurrence of a character in a string.</div>
        <div class="function"><code>ft_strncmp(const char *s1, const char *s2, size_t n)</code> : Compares up to n characters of two strings.</div>
        <div class="function"><code>ft_strnstr(const char *haystack, const char *needle, size_t len)</code> : Locates a substring within a string up to length len.</div>
        <div class="function"><code>ft_strdup(const char *s)</code> : Duplicates a string in new memory.</div>
        <div class="function"><code>ft_substr(const char *s, unsigned int start, size_t len)</code> : Returns a substring starting at a given index.</div>
        <div class="function"><code>ft_strjoin(const char *s1, const char *s2)</code> : Joins two strings into a new string.</div>
        <div class="function"><code>ft_strtrim(const char *s1, const char *set)</code> : Trims characters in set from the start and end of a string.</div>
        <div class="function"><code>ft_split(const char *s, char c)</code> : Splits a string into an array of strings using a delimiter.</div>
        <div class="function"><code>ft_strmapi(const char *s, char (*f)(unsigned int, char))</code> : Applies a function to each character and returns a new string.</div>
    </div>

    <div class="section">
        <h2>3. Memory Functions</h2>
        <div class="function"><code>ft_memset(void *b, int c, size_t len)</code> : Fills memory with a constant byte.</div>
        <div class="function"><code>ft_bzero(void *s, size_t n)</code> : Sets memory to zero.</div>
        <div class="function"><code>ft_memcpy(void *dst, const void *src, size_t n)</code> : Copies n bytes from source to destination.</div>
        <div class="function"><code>ft_memmove(void *dst, const void *src, size_t len)</code> : Copies memory safely even if regions overlap.</div>
        <div class="function"><code>ft_memchr(const void *s, int c, size_t n)</code> : Searches for a byte in memory.</div>
        <div class="function"><code>ft_memcmp(const void *s1, const void *s2, size_t n)</code> : Compares n bytes of memory.</div>
        <div class="function"><code>ft_calloc(size_t count, size_t size)</code> : Allocates memory and initializes it to zero.</div>
    </div>

    <div class="section">
        <h2>4. Conversion Functions</h2>
        <div class="function"><code>ft_atoi(const char *str)</code> : Converts a string to an integer.</div>
        <div class="function"><code>ft_itoa(int n)</code> : Converts an integer to a string.</div>
    </div>

    <div class="section">
        <h2>5. Output Functions</h2>
        <div class="function"><code>ft_putchar_fd(char c, int fd)</code> : Writes a character to a file descriptor.</div>
        <div class="function"><code>ft_putstr_fd(char *s, int fd)</code> : Writes a string to a file descriptor.</div>
        <div class="function"><code>ft_putendl_fd(char *s, int fd)</code> : Writes a string followed by a newline.</div>
        <div class="function"><code>ft_putnbr_fd(int n, int fd)</code> : Writes an integer to a file descriptor.</div>
    </div>

    <p><strong>Note:</strong> This library provides a strong foundation for bigger C projects like <code>printf</code> or <code>get_next_line</code>.</p>
</body>
</html>

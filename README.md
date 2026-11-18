Modified from [upstream](https://github.com/MachaCeleste/SseClientLib):
- Uses `net472` *(for better Unity modding support)*

------

# Usage Example
```cs
private readonly SseClient? _sseClient;
...
_sseClient = new SseClient(endpoint, query, httpClient, keepAliveTimeout);
...
await _sseClient.ConnectAsync(cancellationToken);
```

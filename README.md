# testing-backstage- id: log-message
      name: Log Message
      action: debug:log
      input:
        message: ${{ steps['read-file'].output.content }}
---
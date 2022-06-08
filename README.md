https://liquidjs.com/filters/overview.html


Dear {% if ticket.requester.custom_fields.salutation and ticket.requester.last_name %}{{ticket.requester.custom_fields.salutation | capitalize }} {{ticket.requester.last_name | capitalize }}{% else %}Member{% endif %}​,

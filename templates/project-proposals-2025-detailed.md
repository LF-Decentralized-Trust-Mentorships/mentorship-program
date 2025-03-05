# 2025 Mentorship Projects

{{range .Issues}}
       Issue <a href="{{.HTMLURL}}" class=".btn">{{.Number}}</a>
       {{.Title}}
       {{range .Labels}}<span class="chip">{{.Name}}</span>{{end}}
       {{.Body}}
        Created At {{.CreatedAt}}
{{end}}

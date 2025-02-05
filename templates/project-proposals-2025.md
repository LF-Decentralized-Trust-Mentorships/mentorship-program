# 2025 Mentorship Projects

{{range .Issues}}
<div>
    <table>
        <tr>
            <td>
                Issue <a href="{{.HTMLURL}}" class=".btn">{{.Number}}</a>
            </td>
            <td>
                <b>
                    {{.Title}}
                </b>
            </td>
        </tr>
        <tr>
            <td>
                {{range .Labels}}<span class="chip">{{.Name}}</span>{{end}}
            </td>
            <td>
                {{.Body}}
            </td>
        </tr>
    </table>
    <div class="right-align">
        Created At {{.CreatedAt}}
    </div>
</div>
{{end}}

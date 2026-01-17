Private Sub btnLogin_Click(sender As Object, e As EventArgs) Handles btnLogin.Click
    ' Check if the password length is exactly 6 characters
    If txtPassword.Text.Length <> 6 Then
        ' Show error using the ErrorProvider
        Err.SetError(txtPassword, "Password must be 6 characters long.")
    Else
        ' Clear any previous error
        Err.SetError(txtPassword, "")
        ' Password is valid — you can proceed with login here
        MessageBox.Show("Password is valid. Logging in...")
    End If
End Sub

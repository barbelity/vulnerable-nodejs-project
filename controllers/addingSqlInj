package org.owasp.webgoat.application.documentation_samples;

import org.owasp.webgoat.application.IOException;

import javax.servlet.ServletException;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;
import java.sql.Connection;

public class sqli_vuln {
    protected void doGet(HttpServletRequest request, HttpServletResponse response)
        throws ServletException, IOException {
        Connection connection;
        String query = "SELECT userID FROM users WHERE username = "
                + request.getParameter("username");

        try {
            Statement statement = connection.createStatement();
            ResultSet results = statement.executeQuery( query );
        } catch (Exception e) {
            throw new RuntimeException(e);
        }
    }
    protected void doGet2(HttpServletRequest request, HttpServletResponse response)
        throws ServletException, IOException {
        Connection connection;
        String query = "SELECT userID FROM users WHERE username = "
                + request.getParameter("username");

        try {
            Statement statement = connection.createStatement();
            ResultSet results = statement.executeQuery( query );
        } catch (Exception e) {
            throw new RuntimeException(e);
        }
    }

}

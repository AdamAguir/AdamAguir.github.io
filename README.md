# AdamAguir.github.io

## Hangman

Simple website that uses a Database and php to play hangman.

## Bank App

A Bank application created in asp.net core. It uses Entity Framework to connect the Database

https://github.com/Alex-Bedoya/CS3750BankApp

````
 foreach (Account account in Model.Accounts)
        {
            <div class="row accountDisplay fw-bold">
                <div class="col-3">
                    <label>@account.Type</label>
                </div>
                <div class="col-8">
                @{
                    double amount = account.Balance / 100.0;
                    string strAmount = amount.ToString("0.00");
                }
                    <label class="@(account.Balance > 0 ? "text-success" : "text-danger")">$@strAmount</label>
                </div>
                <a class="mx-auto float-end col-1 btn btn-info" asp-page="AccountDetails" asp-route-Type="@account.Type" asp-route-AccNum="@account.AccountNumber">></a>
            </div>
        }
````

This code creates an html element for each account associated with the user. It is the primary display for the uer's bank account, and also includes a way to view a detailed account view.

## Stock Market Game

The Stock Market game uses ajax methods to refresh the display based on user inputs.

https://github.com/Alex-Bedoya/PlazmaStockGame

## Boggle Game

A Blazor application that utalizes an api for words and SignalR for communication between players.

https://github.com/AdamAguir/PlazmaELGGOB
